# Android Configuration Checker 📱✅

Android Configuration Checker is a command-line tool designed to ensure compliance of Android device configurations with CIS (Center for Internet Security) benchmarks. By leveraging ADB (Android Debug Bridge), it verifies device settings against predefined benchmarks and generates detailed reports, highlighting compliance status. 

![android](https://github.com/saladandonionrings/CIS-Android-Audit/assets/61053314/793a0975-c632-49f2-937c-594d5be8456d)

## Key Features 🚀

- **CIS Benchmark Compliance:** Validate Android device settings against CIS benchmarks to ensure adherence to security best practices. ✔️
- **Custom Checks:** Define custom checks using ADB commands to address specific compliance requirements beyond CIS benchmarks. 🔧
- **Comprehensive Reporting:** Generate detailed Excel reports with compliance status for each verified setting, aiding in audit and remediation efforts. 📊
- **Error Handling:** Robust error handling mechanism ensures accurate compliance assessment, with detailed error reporting for failed commands. ❌

## Getting Started 🛠️

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/saladandonionrings/CIS-Android-Audit.git
   ```
2. Install dependencies:
   ```bash
   cd CIS-Android-Audit
   pip install -r requirements.txt
   ```

### Usage

1. Ensure your Android device is connected to the computer and ADB is enabled.
2. Run the script with the desired device and configuration file:
   ```bash
   python3 cis-audit-android.py --device <device_id> --config <path_to_configuration_file>
   ```

### Configuration File

The configuration file (default : `settings.json`) contains the expected settings and CIS benchmark to be verified.

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements 🙏

- Inspired by CIS benchmarks for Android devices.
- Built with Python and ADB.
