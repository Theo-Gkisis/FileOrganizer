# Directory Organizer

A simple Python script that automatically organizes the files in a directory into subfolders based on their file extensions.

## 📂 What It Does

This script scans a given directory, identifies all files inside it, and organizes them by moving each file into a folder named after its extension.

For example:

```
foto.jpg  →  ./jpg/foto.jpg
report.pdf → ./pdf/report.pdf
script.py  → ./py/script.py
```

## 🚀 Features

* Automatically creates folders for each file extension
* Moves files into their corresponding folders
* Prevents errors by skipping already organized files
* Works with any directory you provide as an argument

## 📦 Installation

Make sure you have Python 3 installed.

Clone the repository:

```bash
git clone https://github.com/yourusername/yourrepo.git
cd yourrepo
```

## 🧠 Usage

Run the script and pass the target folder path:

```bash
python organize.py /path/to/your/folder
```

Example:

```bash
python organize.py C:/Users/Theodoros/Downloads
```

## 📝 Code Overview

### Class: `OrganizeDirectory`

* **`CreateFolders()`**: Creates extension-based folders
* **`OrganizeFiles()`**: Moves files into their appropriate folders
* **`__str__()`**: Returns the directory path string

## 🛠 Requirements

* Python 3.6+
* No external libraries required

## 🤝 Contributing

Feel free to submit pull requests or open issues for improvements.

## 📄 License

This project is open-source and available under the MIT License.
