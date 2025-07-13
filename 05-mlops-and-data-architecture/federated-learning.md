# Federated Learning

_Overview Diagram_

```mermaid
flowchart LR
    A[Decentralized Devices] --> B(Local Models);
    B --> C(Share Model Updates);
    C --> D[Central Server];
    D --> E(Aggregate Updates);
    E --> F[Global Model];
```

### What is Federated Learning?

Federated Learning is a machine learning technique that trains an algorithm across multiple decentralized devices or servers holding local data samples, without exchanging the data itself. This approach addresses critical issues like data privacy, security, and data access rights.

Instead of bringing all the training data to a central server, federated learning brings the model to the data.

### How It Works

The process is iterative and typically follows these steps:

1.  **Distribution:** A central server starts by designing a generic machine learning model (e.g., a neural network) and distributes it to a fleet of local devices (like smartphones, laptops, or servers in different organizations).
2.  **Local Training:** Each device independently trains the model on its own local data. Since the data never leaves the device, user privacy and data security are maintained.
3.  **Aggregation:** Instead of sending the raw data, each device sends only the updated model parameters (the "learnings," such as updated weights and biases) back to the central server. These updates are typically encrypted and much smaller than the raw data.
4.  **Model Improvement:** The central server aggregates all the received updates (e.g., by averaging them) to create an improved, more robust global model.
5.  **Iteration:** This improved global model is then sent back to the devices, and the process repeats, allowing the model to learn from a diverse range of data without centralizing it.

### Three Flavors of Federated Learning

1.  **Horizontal Federated Learning:** This is used when the datasets on different devices share the same feature space but have different samples.
    - **Example:** Two regional hospitals have patient records with the same set of features (e.g., blood pressure, heart rate) but for different groups of patients.

2.  **Vertical Federated Learning:** This applies when datasets on different devices have different features but share the same samples.
    - **Example:** A bank and an e-commerce company have data for the same set of customers, but the bank has their financial history (features) while the e-commerce company has their purchasing history (different features).

3.  **Federated Transfer Learning:** Used when datasets differ in both samples and features. A pre-trained model for one task is adapted for a slightly different task on a different dataset.
    - **Example:** A model trained to identify cars in images is retrained on a separate, decentralized dataset to identify cats.

### Benefits

- **Data Privacy and Security:** The most significant advantage. Raw data remains on the local device, minimizing risks associated with data breaches and complying with regulations like GDPR.
- **Collaborative Learning:** Enables multiple organizations to collaborate on building a powerful ML model without sharing their sensitive proprietary data.
- **Reduced Network Load:** Transmitting small model updates is far more efficient than transmitting large raw datasets.

### Challenges

- **Communication Overhead:** Requires frequent communication between the server and devices, which can be a bottleneck.
- **Data Heterogeneity:** Data on different devices can be non-IID (Not Independent and Identically Distributed), which can bias the model and slow down convergence.
- **Security Risks:** Although data is not shared, there is still a risk of "inference attacks," where malicious actors could try to deduce sensitive information from the shared model updates. Techniques like secure aggregation and differential privacy are used to mitigate this.

### Use Cases

- **Healthcare:** Hospitals can collaborate to train diagnostic models on patient data without sharing confidential patient records.
- **Finance:** Banks can improve fraud detection models by learning from transaction patterns across different institutions without revealing customer data.
- **Mobile Devices:** Improving predictive keyboards (like Gboard) by learning from user typing patterns on individual phones.

### Reference

[Federated Learning Explained](https://www.youtube.com/watch?v=I23-L3ED0tI) by [IBM Technology](https://www.youtube.com/@IBMTechnology)
