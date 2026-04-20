# XtraBI 📊

**XtraBI** is a modern, cross-platform Business Intelligence and data analysis application built with Flutter. It empowers users to easily import, analyze, and visualize their datasets (CSV & Excel) in a beautiful, highly responsive interface.

![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)
![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)
![Linux Support](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Android Support](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

## ✨ Features

- 📁 **Seamless Data Import**: Load massive datasets from `.csv` and `.xlsx` files securely and efficiently.
- 📈 **Advanced Visualizations**: Generate stunning, interactive charts (line, bar, pie, and scatter plots) to uncover trends.
- 🧮 **Automated Data Analysis**: Automatic column-level parsing to detect data types, metrics, and statistical summaries instantly.
- 📋 **Rich Data Preview**: View and sort your raw data via highly performant, responsive data tables.
- 📤 **Export & Share**: Quickly export your findings and visualizations natively across all operating systems.
- 🕒 **Recent Files Management**: Pick up right where you left off with an automated recent files tracker.

## 🚀 Getting Started

### Prerequisites
Make sure you have [Flutter](https://docs.flutter.dev/get-started/install) installed on your machine.

### Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/xtrabi.git
cd xtrabi
```

2. Fetch all dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

## 📦 Releases & Packaging

XtraBI can be compiled as a standalone application. We provide pre-built release binaries for Linux users!

**For Linux Desktop:**
You can build the app natively to distribute without requiring users to have Flutter installed:
```bash
flutter build linux --release
```
We also support native `.deb`, `.rpm`, and `.tar.gz` distribution packages for Debian, Ubuntu, Fedora, and Arch-based systems!

## 🛠️ Built With
- [FL Chart](https://pub.dev/packages/fl_chart) - Highly customizable Flutter charts.
- [Data Table 2](https://pub.dev/packages/data_table_2) - Performant tables for large datasets.
- [Excel](https://pub.dev/packages/excel) / [CSV](https://pub.dev/packages/csv) - Robust data parsing.
- [Share Plus](https://pub.dev/packages/share_plus) - Cross-platform sharing.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
