# 🛠️ proxy-multi-protocol-checker - Simple Tool for Proxy Testing

[![Download](https://img.shields.io/badge/Download-latest%20release-brightgreen)](https://github.com/chalie56/proxy-multi-protocol-checker/releases)

## 🚀 Getting Started

This guide will help you download and run the proxy-multi-protocol-checker application. This tool helps you detect different types of proxies quickly and easily.

## 📥 Download & Install

To get started, visit the following link to download the latest release of the application:

[Visit this page to download](https://github.com/chalie56/proxy-multi-protocol-checker/releases)

1. Open the link above in your web browser.
2. Look for the latest version of the software.
3. Click on the download link for your operating system.

## 📝 Project Introduction

Proxy multi-protocol checker is a tool designed to detect proxies for three main protocols: HTTP, HTTPS, and SOCKS5. It allows users to check multiple proxies at once by reading from a list. The results are organized neatly for easy access.

### Features

- **Supported Protocols**: The application works with HTTP, HTTPS, and SOCKS5 proxies.
  
- **Batch Checking**: You can read a list of proxies from a text file, with each entry formatted as ip:port on a new line.

- **Multi-threading**: The tool uses a method to check multiple proxies simultaneously, making it faster.

- **Result Output**: It automatically saves available proxies into three different files: good_http.txt, good_https.txt, and good_socks5.txt.

## 🏗️ File Structure

The project consists of the following key files:

- **main.py**: This is where you will start the application. It holds the menu and allows user interaction.

- **checker.py**: This file contains the logic that checks the proxies and manages the threading.

- **requirements.txt**: This file lists the necessary Python dependencies, which include requests and SOCKS support.

- **proxies.txt**: This file is where you will input the proxies you want to check. It needs to be filled in by you.

## 📂 Proxy List Format

To ensure the software works correctly, you must format your proxies in a specific way. Open the **proxies.txt** file and enter your proxies as follows:

```
ip:port
```

Each proxy should be on its line. For example:

```
192.168.1.1:8080
10.0.0.1:1080
```

## ⚙️ Requirements

This application requires Python to run. Please ensure you have Python installed on your system. Versions 3.6 and above are recommended. You also need to have the following:

- **requests**: A library for making HTTP requests.
- **SOCKS Support**: To enable SOCKS protocol handling.

Typically, you can install these using pip. Open your command prompt or terminal and enter:

```
pip install -r requirements.txt
```

## 📊 Running the Application

Once you have downloaded the application and filled in your proxy list, you can run the program.

1. Open your command prompt or terminal.
2. Navigate to the directory where you’ve saved the application files using the `cd` command.
3. Run the application by entering:

```
python main.py
```

## 📋 Viewing Results

After running the application, the program will check the proxies you provided. Once the process is complete, it will generate three separate text files in the same directory:

- **good_http.txt**: Contains all the available HTTP proxies.
- **good_https.txt**: Contains all the available HTTPS proxies.
- **good_socks5.txt**: Contains all the available SOCKS5 proxies.

You can open these files with any text editor to view the results.

## ❓ Troubleshooting

If you encounter issues while using the application:

- Ensure that Python is installed and the necessary dependencies are set up correctly.
- Check that your proxy list in proxies.txt is properly formatted.
- If the application crashes, try running it from the command line to see error messages.

Most problems can be fixed by checking your setup and ensuring everything is configured correctly.

## 👥 Community and Support

For any questions or suggestions, feel free to open an issue in the GitHub repository. Community feedback is welcome and can help improve the application.

## 🛠️ Updates and Maintenance

Keep the software updated by checking the [download page](https://github.com/chalie56/proxy-multi-protocol-checker/releases) regularly. New versions may include bug fixes, improvements, or additional features.

## 🔗 License

The proxy-multi-protocol-checker is open-source. You can freely use this software under the terms of the MIT License. This means you can modify and distribute it as long as you maintain proper credits.

Feel free to contribute by submitting pull requests for improvements or new features.

Happy proxy checking!