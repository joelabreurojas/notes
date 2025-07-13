# C vs. C++ Syntax Comparison

This note compares a simple function implemented in both C and modern C++ to highlight differences in syntax and style.

### C Syntax

The C implementation uses a standard `for` loop and `if` statements for control flow.

```c
int calculate(int bottom, int top)
{
    if (top > bottom)
    {
        int sum = 0;

        for (int number = bottom; number <= top; number++)
        {
            if (number % 2 == 0)
            {
                sum += number;
            }
        }

        return sum;
    }
    else
    {
        return 0;
    }
}
```

### C++ Syntax

The modern C++ version leverages the `ranges` library for a more functional and declarative approach, using pipes to chain operations.

```cpp
namespace stdviews = std::views;

int calculate(int bottom, int top) {
    return top <= bottom ? 0 :
        std::ranges::fold_left(
            stdviews::iota(bottom, top + 1) |
            stdviews::filter([](auto n) { return n % 2 == 0; }), 0, std::plus<>{});
}
```
