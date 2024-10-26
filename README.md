# Stellar Sorobon Rust Tutorials

Welcome to the **Stellar Sorobon Rust Tutorials**! This repository provides a hands-on, beginner-friendly guide to building smart contracts using **Soroban** on the Stellar blockchain with the **Rust programming language**. Whether you're new to Stellar, Soroban, or Rust, these tutorials will help you understand the basics and advance step-by-step through real-world contract examples.

---

## Table of Contents

1. **Introduction to Stellar and Soroban**
2. **Setting Up the Development Environment**
3. **Getting Started with Rust Basics**
4. **Writing Your First Soroban Smart Contract**
5. **Testing and Debugging Soroban Contracts**
6. **Interacting with Stellar Accounts and Assets**
7. **Deploying Contracts on Testnet**
8. **Integrating Frontend with Soroban Smart Contracts**
9. **Advanced Topics: Cross-contract Calls, Storage, and Events**
10. **Resources and Further Learning**

---

## Prerequisites

Before diving into the tutorials, make sure you have the following:

- **Rust Installed**: [Install Rust](https://www.rust-lang.org/tools/install) (latest stable version)
- **Soroban CLI**: [Soroban CLI Documentation](https://soroban.stellar.org/docs/cli)
- **Stellar Account** on Testnet: [Stellar Laboratory](https://laboratory.stellar.org/#account-creator?network=test)
- Basic understanding of **blockchain technology** (Optional but helpful)
- Familiarity with **command-line interface** usage

---

## Getting Started

1. **Clone the Repository**

   ```bash
   git clone https://github.com/kunaldhongade/stellar-soroban-rust-tutorials.git
   cd stellar-soroban-rust-tutorials
   ```

2. **Install Rust and Soroban CLI**
   Follow the installation steps in the tutorial folder for the Rust toolchain and Soroban CLI setup.

3. **Run Your First Tutorial**
   Navigate to the relevant tutorial folder and start with:

   ```bash
   cd tutorial-01-hello-world
   cargo build
   ```

4. **Deploy and Test Your Contracts**
   Use the included scripts to deploy contracts to the Stellar testnet and perform basic tests:
   ```bash
   soroban deploy --wasm target/wasm32-unknown-unknown/release/your_contract.wasm
   ```

---

## Repository Structure

```
stellar-soroban-rust-tutorials/
│
├── tutorial-01-hello-world/        # Basic contract example
├── tutorial-02-token-transfer/     # Token handling using Soroban
├── tutorial-03-cross-contract/     # Cross-contract interaction
├── advanced-topics/                # Additional, advanced examples
└── README.md                       # You're reading it!
```

---

## Contributing

We welcome contributions! Feel free to submit pull requests, report issues, or suggest improvements to enhance the learning experience.

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b my-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add awesome feature"
   ```
4. Push the branch:
   ```bash
   git push origin my-feature
   ```
5. Open a pull request.

---

## Support

If you encounter issues or need help, please open an issue in the repository or reach out through:

- **Stellar Soroban Documentation**: [Soroban Docs](https://soroban.stellar.org/docs)
- **Stellar Developers Forum**: [Stellar Community](https://community.stellar.org/)

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

## Acknowledgments

Special thanks to the **Stellar Development Foundation (SDF)** for providing excellent resources, and the broader Stellar community for their contributions and support.

---

Happy coding and welcome to the Stellar ecosystem 🚀!
