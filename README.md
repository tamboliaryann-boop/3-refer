# Telegram Referral Bot Documentation

## Overview
This Telegram Referral Bot allows users to create and manage referral links to grow their community and reward members for bringing in new users.

## Features
- Create personalized referral links
- Track referrals and rewards
- Easily configurable settings
- Integration with Telegram bots

## Setup Instructions
1. **Clone the repository**:
   ```bash
   git clone https://github.com/tamboliaryann-boop/3-refer.git
   cd 3-refer
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Create a Telegram Bot**:
    - Use [BotFather](https://core.telegram.org/bots#botfather) to create a new bot and get your API token.

4. **Configure the bot**:
   - Create a `.env` file in the root of the project and add the following:
     ```
     TELEGRAM_BOT_TOKEN=YourBotsTokenHere
     ```

5. **Run the bot**:
   ```bash
   node index.js
   ```

## Usage
To use the bot, simply send your referral link to your friends. They can join by clicking the link, and you'll earn rewards for each new user that signs up through your link.

## Configuration Details
- The bot supports various configurations, including reward percentages and custom messages. These can be adjusted in the `.env` file or directly within the codebase.

## Contribution
Feel free to submit issues, feature requests, or pull requests to enhance the bot's capabilities!