# SiL-Simulink-with-Python

This side project bridges the gap between MATLAB/Simulink and Python, enabling seamless integration for Software-in-the-Loop (SiL) testing. This project allows you to:

- Run **Simulink models and libraries** directly within Python environments.
- Execute **Python code** within Simulink models.


## Features

- **Bidirectional Integration**: Seamlessly run Simulink models in Python and embed Python scripts within Simulink.
- **Efficient SiL Testing**: Accelerate testing workflows by reducing Simulink overhead.
- **Precompiled Libraries**: Utilize precompiled Simulink models as shared libraries for faster execution.
- **Automation Ready**: Integrate with Python’s testing frameworks like `pytest` for automated testing.
- **License-Free Distribution**: Share and run tests on machines without MATLAB/Simulink licenses.
- **Cloud Compatibility**: Implement continuous integration and testing using platforms like GitHub Actions and GitLab CI.

## Motivation

### Simulink for Everyone

The integration addresses several challenges faced by engineers and developers working with Simulink:

- **Reduced Overhead**: Simulink’s dependency on MATLAB can slow down SiL tests. This project minimizes that overhead.
- **Performance**: Precompiled shared libraries offer faster execution compared to traditional model references.
- **Automation**: Python’s robust automation tools streamline testing processes.
- **Accessibility**: Distribute and run tests without requiring MATLAB/Simulink licenses, broadening access.
- **Collaboration**: Enable Python developers to collaborate on Simulink projects, fostering a more inclusive development environment.

### Python for Simulink

By integrating Python with Simulink, you can harness Python’s versatility to enhance Simulink’s capabilities:

- **Extensive Libraries**: Utilize Python’s vast array of libraries for data analysis, machine learning, and more within Simulink models.
- **Scripting and Customization**: Write custom scripts to control and manipulate Simulink models dynamically.
- **Enhanced Testing**: Implement sophisticated testing strategies using Python’s testing frameworks.
- **Scalability**: Scale testing workflows using Python’s concurrency and parallelism features.

## Key Use Cases

- **Running Simulink Models in Python**: Integrate and execute complex Simulink models within Python scripts for advanced analysis and processing.
- **Automated SiL Testing**: Leverage Python and `pytest` to create automated testing pipelines for Simulink subsystems.
- **Licenseless Algorithm Sharing**: Distribute Simulink-based algorithms to team members without MATLAB/Simulink licenses.
- **Cloud Testing Automation**: Utilize CI/CD platforms like GitHub Actions or GitLab CI to run automated tests in the cloud, ensuring continuous integration and delivery.

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/CagriCatik/SiL-Simulink-with-Python.git
   cd SiL-Simulink-with-Python
   ```

2. **Create a Virtual Environment**

   ```bash
   python3 -m venv venv
   source venv/bin/activate 
   ```

3. **Install Python Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Build Simulink Shared Libraries**

   Follow the instructions in the [Building Shared Libraries](docs/building_shared_libraries.md) guide to compile your Simulink models into shared libraries.

## Getting Started

1. **Configure Your Simulink Models**

   Ensure your Simulink models are set up for code generation. Follow the guidelines in the [Simulink Setup](docs/simulink_setup.md) documentation.

2. **Integrate with Python**

   Use the provided Python API to load and interact with your Simulink models. Refer to the [API Reference](docs/api_reference.md) for detailed usage.

3. **Run Tests**

   Implement and execute your automated tests using `pytest` or your preferred testing framework. See [Testing Guide](docs/testing_guide.md) for examples.
