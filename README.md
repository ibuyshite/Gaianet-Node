# Ultimate Gaia AI Airdrop Farming Guide

Welcome to the **Ultimate Gaia AI Airdrop Farming Guide**! This guide will walk you through the entire process of setting up and running a Gaia node to farm airdrops using the lightweight LLM model **Qwen2 0.5B Instruct**. Whether you're a beginner or an experienced user, this guide will help you maximize your Gaia XP earnings.

---

## Table of Contents
1. [System Requirements](#system-requirements)
2. [Setting Up Your Environment](#setting-up-your-environment)
   - [For Windows Users](#for-windows-users)
   - [For Linux Users](#for-linux-users)
3. [Installing Gaia Node CLI](#installing-gaia-node-cli)
4. [Downloading Config and LLM Model](#downloading-config-and-llm-model)
5. [Running Your Gaia Node](#running-your-gaia-node)
6. [Registering Your Node on Gaia Website](#registering-your-node-on-gaia-website)
7. [Joining a Domain](#joining-a-domain)
8. [Chatting with Your Node](#chatting-with-your-node)
9. [Automating Chat with Python Script](#automating-chat-with-python-script)
10. [Buying Your Own Domain](#buying-your-own-domain)
11. [Troubleshooting and Support](#troubleshooting-and-support)

---

## System Requirements
To run a Gaia node with the **Qwen2 0.5B Instruct** model, ensure your system meets the following minimum requirements:

- **CPU**: 6 cores
- **RAM**: 8GB
- **VRAM**: 8GB (optional but recommended)
- **Storage**: 10GB free space
- **Internet**: Stable and decent speed

**Note**: Avoid using VPS plans for running Gaia nodes, as they perform poorly. Instead, use a local machine running Windows or Linux. If VPS is the only option you, Go for it.

---

## Setting Up Your Environment

### For Windows Users
1. **Enable WSL (Windows Subsystem for Linux)**:
   - Open PowerShell as Administrator and run:
     ```bash
     wsl --install
     ```
   - Restart your computer if prompted.

2. **Enable Virtualization in BIOS**:
   - **For Intel CPUs**:
     - Restart your computer and enter BIOS/UEFI settings.
     - Look for "Intel VT-x" or "Virtualization Technology" and enable it.
   - **For AMD CPUs**:
     - Restart your computer and enter BIOS/UEFI settings.
     - Look for "AMD-V" or "SVM Mode" and enable it.

3. **Install Ubuntu on WSL**:
   - Open Microsoft Store and search for "Ubuntu".
   - Install the latest version of Ubuntu.
   - Launch Ubuntu from the Start menu and complete the setup.

4. **Update and Upgrade Ubuntu**:
   - Run the following commands in the Ubuntu terminal:
     ```bash
     sudo apt update && sudo apt upgrade -y
     ```

5. **Install Python3**:
   - Run:
     ```bash
     sudo apt install python3
     ```

### For Linux Users
1. **Update and Upgrade System**:
   - Run:
     ```bash
     sudo apt update && sudo apt upgrade -y
     ```

2. **Install Python3**:
   - Run:
     ```bash
     sudo apt install python3
     ```

---

## Installing Gaia Node CLI
To install the Gaia Node CLI, run the following command:

```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

After installation, restart your terminal or relogin to update the CLI in your bash environment.

---

## Downloading Config and LLM Model
To download the **Qwen2 0.5B Instruct** model and its configuration, run:

```bash
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen2-0.5b-instruct/config.json
```

---

## Running Your Gaia Node
- **Start the Node**:
  ```bash
  gaianet start
  ```

- **Stop the Node**:
  ```bash
  gaianet stop
  ```

---

## Registering Your Node on Gaia Website
1. **Sign Up on Gaia**:
   - Visit [Gaia Signup](https://gaianet.ai/reward?invite_code=Rf0Axf) and complete the registration.

2. **Complete Social Tasks**:
   - Go to [Reward Summary](https://www.gaianet.ai/reward-summary) and complete the tasks.

3. **Add Your Node**:
   - Visit [Node Settings](https://www.gaianet.ai/setting/nodes) and click **Connect New Node**.
   - Run the following command to get your **Node ID** and **Device ID**:
     ```bash
     gaianet info
     ```
   - Copy and paste the IDs into the website and click **Join**.

---

## Joining a Domain
1. **Join a Domain**:
   - Go to [Node Settings](https://www.gaianet.ai/setting/nodes).
   - Click the three dots next to your active node and select **Join Domain**.
   - Search for the domain **mefury.gaia.domain** and complete the steps.
**DM me on Discord if you joined my domain for any help and instructions regarding Gaia(Social Links are in the last part)**

2. **Verify Compatibility**:
   - Ensure your node's LLM model matches the domain's model.

---

## Chatting with Your Node
To interact with your node and earn XP, visit:
- [Mefury Gaia Domain](https://mefury.gaia.domains)

Don't forget to convert Gaiapoints to CreditBalance everyday(Your Gaiapoints will remain same after converting and You can convert 1000 gaiapoints everyday)

---

## Automating Chat with Python Script(This earns you more Gaia Users XP🔥)
1. **Create an API Key**:
   - Go to [Gaia API Keys](https://www.gaianet.ai/setting/gaia-api-keys) and create a new key. Save the API key somewhere cz you wont be able to access it again.

2. **Download the Python Script**:
   - Run:
     ```bash
     curl -L -o gaiabot.py https://github.com/mefury/Ultimate-Gaia-Airdrop-Guide/raw/main/gaiabot.py
     ```

3. **Run the Script**:
   - Now run this command to start the bot:
     ```bash
     python3 gaiabot.py
     ```
   - Enter your Gaia API key when prompted.

Note: to run the bot in the background all the time, create a screen using
```bash
screen -S gaiabot
```
Run the bot here and press Ctrl + A + D to quit the screen.
To to check if the bot is running run
```bash
screen -ls
```
Copy the whole gaianet screen ID and run
```bash
screen -r pastegaianetIDhere
```
Now press enter and you will be able to see logs again, To stop the bot press Ctrl + C
---

## Buying Your Own Domain
To purchase your own domain, visit:
- [Gaia Domain Purchase](https://www.gaianet.ai/gaia-domain-name?referralCode=Rf0Axf)  
  **Referral Code**: Rf0Axf (supports my work!)

---

## Troubleshooting and Support
If you encounter any issues or need assistance, feel free to reach out:
- **Discord**: @mefury
- **Twitter**: [@meefury](https://x.com/meefury)

---

Congratulations! You’ve successfully set up your Gaia node and are ready to farm airdrops. Happy farming! 🚀
