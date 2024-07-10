# Chaos Guru

![GitHub release (latest by date)](https://img.shields.io/github/v/release/yourusername/chaos-guru)
![GitHub issues](https://img.shields.io/github/issues/yourusername/chaos-guru)
![GitHub pull requests](https://img.shields.io/github/issues-pr/yourusername/chaos-guru)
![GitHub](https://img.shields.io/github/license/yourusername/chaos-guru)

## Overview

Chaos Guru is a powerful chaos engineering tool designed to help you identify weaknesses and improve the resilience of your cloud-native applications. Chaos Guru allows you to introduce controlled chaos into your Kubernetes clusters, enabling you to test the reliability and stability of your systems under various failure conditions.

This project is currently in the bootstrap phase, and we aim to build a robust community around Chaos Guru. Join us in making applications more resilient!

## Features

- **Pod Fault Chaos**: Simulate pod failures to test application robustness.
- **Network Chaos**: Introduce network latency, packet loss, and other network-related issues.
- **IO Chaos**: Disrupt IO operations to evaluate the handling of disk-related failures.
- **Scheduler**: Schedule chaos experiments at specific times and intervals.
- **Web Dashboard**: Manage and monitor chaos experiments through a user-friendly interface.
- **Observability Integration**: Collect and visualize logs and metrics for real-time monitoring.

## Getting Started

Follow these instructions to set up and run Chaos Guru in your environment.

### Prerequisites

- Kubernetes cluster (version 1.18 or higher)
- Go (version 1.16 or higher)
- Docker

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/chaos-guru.git
    cd chaos-guru
    ```

2. Install dependencies:
    ```bash
    go mod tidy
    ```

3. Deploy the controller to your Kubernetes cluster:
    ```bash
    make deploy
    ```

4. Access the web dashboard:
    ```bash
    make run
    ```

## Contributing

We welcome contributions from the community! Please read our [Contributing Guide](CONTRIBUTING.md) to get started.

## License

Chaos Guru is licensed under the Apache 2.0 License. See the [LICENSE](LICENSE) file for more details.

## Roadmap

- [x] Initial project setup
- [ ] Implement Pod Fault Chaos
- [ ] Implement Network Chaos
- [ ] Implement IO Chaos
- [ ] Develop Web Dashboard
- [ ] Add Observability Integration
- [ ] Build a vibrant community

## Contact

For any questions or suggestions, feel free to open an issue.
