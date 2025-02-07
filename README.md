# Gaianet AI Airdrop Farming Guide

Welcome to the **Ultimate Gaia AI Airdrop Farming Guide**! This guide will walk you through the entire process of setting up and running a Gaia node to farm airdrops using the lightweight LLM model **Qwen2 0.5B Instruct**. Whether you're a beginner or an experienced user, this guide will help you maximize your Gaia XP earnings.

---

## System Requirements
To run a Gaia node with the **Qwen2 0.5B Instruct** model, ensure your system meets the following minimum requirements:

- **CPU**: 6 cores
- **RAM**: 8GB
- **VRAM**: 8GB (optional but recommended)
- **Storage**: 10GB free space
- **Internet**: Stable and decent speed

---

## Setting Up Your Environment

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
To download the **Llama-3.2-1B** model and its configuration, run:

```bash
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/llama-3.2-1b-instruct/config.json
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
   - Visit [Gaia Signup](https://gaianet.ai/reward?invite_code=RVdsfB) and complete the registration.

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
- [Henlo Gaia Domain](https://henlo.gaia.domains)

Don't forget to convert Gaiapoints to CreditBalance everyday(Your Gaiapoints will remain same after converting and You can convert 1000 gaiapoints everyday)

---

## Automating Chat with Python Script(This earns you more Gaia Users XP🔥)
1. **Create an API Key**:
   - Go to [Gaia API Keys](https://www.gaianet.ai/setting/gaia-api-keys) and create a new key. Save the API key somewhere cz you wont be able to access it again.

2. **Download the Python Script**:
   - Run:
     ```bash
     curl -L -o gaiabot.py https://github.com/ibuyshite/Gaianet-Node/raw/main/gaiabot.py
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
screen -r gaiabot
```
Now press enter and you will be able to see logs again, To stop the bot press Ctrl + C
---

---

Congratulations! You’ve successfully set up your Gaia node and are ready to farm airdrops. Happy farming! 🚀
