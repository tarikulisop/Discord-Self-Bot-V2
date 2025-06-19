# SELFCORD V4 - Discord Selfbot

**SELFCORD V4** is a powerful Discord selfbot created by `tarikul.real` that provides a wide range of features for automating and enhancing your Discord experience.

## ✨ Features

### 🔹 General Features
```
.csrv <copy_id> <target_id>  # Clone server
.srvinfo                     # Show server info
.user_info @user             # Get user information
.yt <search_query>           # YouTube search
.abuse @user                 # Generate random abuse
```
💰 Crypto Features
```
.send <address> <amount>     # Send LTC
.bal <address>               # Check LTC balance
.mybal                       # Check your LTC balance
.ltc                         # Get LTC price
.i2c <amount>                # INR to Crypto conversion
.ltcqr <address> <usd_amt>   # Generate LTC QR code
```
📨 Message Features
```
.spam 10 <message>           # Spam messages
.dm @user <message>          # DM a user
.ar <trigger>, <response>    # Add auto-response
.clear 50                    # Delete messages
.translate en fr <text>      # Translate text
```
🎭 Fun Features
```
.joke                        # Get random joke
.meme                        # Get random meme
.rizz @user                  # Send pickup line
.nitro                       # Generate fake nitro
.blurpify @user              # Blurpify someone
```
🛠️ Installation
Install Python 3.8+
```
# Windows
winget install Python.Python.3.8

# Linux
sudo apt install python3.8
```
Install dependencies: 
```
pip install -r requirements.txt
```
Configure config.json:
```

{
    "token": "YOUR_DISCORD_TOKEN",
    "prefix": ".",
    "LTC_ADDY": "your_ltc_address",
    "bkash": "your_bkash_number"
}
```
Run the bot:
```
python bot.py
```
# or on Windows:
```
run.bat
```
🌐 Support
For support and emojis:
[PartnerOP Discord]()

For hosting:
Glacier Host
