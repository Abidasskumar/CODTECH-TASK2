# Web App Pen Testing

Welcome to the **Web App Pen Testing** project! This repository provides a step-by-step guide to performing a basic penetration test on a web application using Nessus Essentials.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Steps](#steps)
  1. [Login to Nessus Essentials](#1-login-to-nessus-essentials)
  2. [Select Basic Scan Option](#2-select-basic-scan-option)
  3. [Select Scan Type](#3-select-scan-type)
  4. [Launch the Scan](#4-launch-the-scan)
  5. [Review Vulnerabilities](#5-review-vulnerabilities)
  6. [Analyze Remediations](#6-analyze-remediations)
- [Conclusion](#conclusion)
- [License](#license)

## Introduction

This project focuses on using Nessus Essentials to conduct a basic penetration test on a web application. The objective is to identify vulnerabilities and provide remediation suggestions to enhance the security of the target web application.

## Prerequisites

Before starting, ensure you have the following:

- An active [Nessus Essentials](https://www.tenable.com/products/nessus/nessus-essentials) account.
- Basic knowledge of web application architecture.
- The IP address or domain of the target web application.

## Installation

1. [Download and install Nessus Essentials](https://www.tenable.com/products/nessus/nessus-essentials).
2. Follow the setup instructions to configure the tool.

## Steps

### 1. Login to Nessus Essentials

- Open Nessus Essentials and log in with your credentials.

### 2. Select Basic Scan Option

- Navigate to the dashboard.
- Select `Basic Scan` and enter the target details, such as the IP address or domain of the web application.

### 3. Select Scan Type

- Choose from the following scan types:
  - **Port Scan:** Identify open ports and services.
  - **Vulnerability Scan:** Detect known vulnerabilities in the target's software and configurations.

### 4. Launch the Scan

- After selecting the scan type and entering the target details, click `Launch` to start the scan.

### 5. Review Vulnerabilities

- Once the scan is complete, review the list of detected vulnerabilities.
- Each vulnerability will include details on its severity and potential impact.

### 6. Analyze Remediations

- Nessus Essentials provides remediation suggestions alongside each vulnerability.
- Use these recommendations to patch or mitigate the identified issues.

## Conclusion

This process allows for the identification of security weaknesses within a web application. Addressing the detected vulnerabilities is crucial to ensuring the application's security.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
