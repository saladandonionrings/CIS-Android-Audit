# Android Security Configuration Checker 📱

Android Security Configuration Checker is a command-line tool designed to ensure compliance of Android device configurations with CIS (Center for Internet Security) benchmarks. 

![android](https://github.com/saladandonionrings/CIS-Android-Audit/assets/61053314/793a0975-c632-49f2-937c-594d5be8456d)

## Functionalities

- **CIS Benchmark Compliance:** validate Android device settings against CIS benchmarks to ensure security best practices.
- **Custom checks:** Define custom checks using ADB commands to address specific compliance requirements beyond CIS benchmarks.
- **Reporting:** Generate detailed CSV reports with compliance status for each verified setting.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/saladandonionrings/CIS-Android-Audit.git
   ```
2. Install dependencies:
   ```bash
   cd CIS-Android-Audit
   pip3 install -r requirements.txt
   ```

### Usage

1. Ensure your Android device is connected to your computer and ADB is enabled.
2. Run the script with your device and configuration file:
   ```bash
   python3 cis-audit-android.py --device <device_id> --config <path_to_configuration_file>
   ```

### Configuration File

The configuration file (default : `settings.json`) contains the expected settings and CIS benchmark to be verified.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Inspired by CIS benchmarks for Android devices.
- Built with Python and ADB.
