# Simple TM Bot
## Features

- Installs necessary dependencies for running the bot
- Provides an easy way to link the bot to a phone number
- Re-link the bot if it gets disconnected or removed from your device
- Simple instructions to get started quickly

## Prerequisites

Before you begin, ensure that you have the following:

- A device with Termux installed
- A stable internet connection
- Node.js and Git installed on your system

## Step 1 - Installation

Follow these steps to set up and run the bot:

1. **Update and upgrade system packages**  
   Run the following command to update and upgrade your Termux packages:
   ```bash
   pkg update -y && pkg upgrade -y
2. **Install Node.js and Git**
   These are necessary for running the bot:
   ```bash
   pkg install -y nodejs git
3. **Clone the repository**
   Clone the GitHub repository to your local machine:
   ```bash
   git clone https://github.com/coderxsa/simple-tm-bot.git

4. **Navigate to the project directory**
   Move into the cloned repository:
   ```bash
   cd simple-tm-bot
5. **Install dependencies**
   Install the necessary dependencies using npm:
   ```bash
   npm install
6. **Run the bot**
   Run the bot with the following command (replace 27938337 with your specific phone number):
   ```bash
   node index.js 27938337


## Step 2 - Relink Bot

In case the Termux session disconnects or you need to relink the bot:

1. **Relink the bot**
  Run the following commands:
   ```bash
   cd simple-tm-bot
   node index.js 27938337

2. **Reinstall the bot**
   If you have removed the linked device, you will need to reinstall the bot like step 1:

   Clear data in Termux (Go to Android Settings > Apps > Termux > Clear Data)
   Follow the installation process again
   ```bash
   pkg update -y && pkg upgrade -y
   pkg install -y nodejs git
   git clone https://github.com/coderxsa/simple-tm-bot.git
   cd simple-tm-bot
   npm install
   node index.js 27938337


