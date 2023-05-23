# **CIA Triad PowerShell Scripts**
This repository contains a collection of PowerShell scripts that are designed to enhance and support the principles of the CIA Triad (Confidentiality, Integrity, and Availability) in information security. These scripts aim to provide useful functionalities and automate various tasks related to ensuring the security and protection of data and systems.

## Table of Contents
* Introduction
* Scripts
* Usage
* Contributing
* License

## Introduction
The CIA Triad is a foundational concept in information security, representing the three core principles that contribute to the security of data and systems. These principles are:

1. **Confidentiality**: Ensuring that sensitive information is only accessible to authorized individuals or systems.
1. **Integrity**: Maintaining the accuracy, consistency, and trustworthiness of data and systems.
1. **Availability**: Ensuring that data and systems are accessible and usable when needed.

PowerShell is a powerful scripting language and automation framework that is widely used in Windows environments. This repository aims to provide a collection of PowerShell scripts that can help security professionals and system administrators in achieving and maintaining the CIA Triad objectives.

## Scripts
The repository currently includes the following scripts:
1. **csv_Merge_Script.ps1**: This script retrieves the start and end dates, creates a file name based on those dates, merges CSV files from a specified folder into a single variable, saves the merged content to a new CSV file with the generated file name in a target directory, and finally removes all other CSV files in the source folder except for the newly created file.

1. **Security_csv_Merge_Script.ps1**: This script sets the path where the security logs will be saved, retrieves the start date (7 days ago from the current date), gets the name of the current computer, retrieves security events from the specified server starting from the start date, selects specific properties from the events, and exports them to a CSV file with a filename that includes the server name and the current date and time.

1. **System_csv_Merge_Script.ps1**: This script sets the path where the system logs will be saved, retrieves the start date (7 days ago from the current date), gets the name of the current computer, retrieves system events from the specified server starting from the start date, selects specific properties from the events (including ID, Message, Level, EventRecordID, and Timestamp), and exports them to a CSV file with a filename that includes the server name and the current date and time.

## Usage
Each script in this repository is self-contained and can be executed independently. Before using a script, please review the script's documentation and comments to understand its purpose, inputs, and any specific requirements.

## Contributing
Contributions to this repository are welcome! If you have additional PowerShell scripts that align with the CIA Triad principles or have improvements to the existing scripts, feel free to open an issue or submit a pull request.

## License
The scripts in this repository are provided under the MIT License. Feel free to use, modify, and distribute the scripts in accordance with the terms of the license.

Please note that while these scripts aim to enhance the security of your systems, they are provided as-is without any warranty. Use them at your own risk and ensure to review and understand their functionality before running them in production environments.