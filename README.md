📞 Contact

> [Termux guides if you run on mobile](https://github.com/MeoMunDep/Guides-for-using-my-script-on-termux.)

> If you encounter any issues or have questions, feel free to reach out:

- Contact: [Link](t.me/MeoMunDep)
- Group: [Link](t.me/KeoAirDropFreeNe)
- Channel: [Link](t.me/KeoAirDropFreeNee)

> > > Help me with your referral [Link](https://t.me/pitchtalk_bot/app?startapp=38f044)

## 🚀 Getting Started

> Remember to download Nodejs version: **22.11.0** and NPM version: **10.9.0**


To get started with the bot, follow these steps:

0. **Dowload NodeJS to run the bot**
Before running the bot, make sure you have the following installed:

- **Node.js** (Version: `22.11.0`)
- **npm** (Version: `10.9.0`)

Download Node.js and npm here: [Download Link](https://t.me/KeoAirDropFreeNe/257/1462).

-> Double click on `setup.bat` for windows or `setup.sh` for linux/mac if you want to run automatically, remember to fill all the necessary data.

1. **Install Dependencies and Modules:**

   ```
   npm i user-agents cloudscraper axios colors https-proxy-agent socks-proxy-agent
   ```

2. **Prepare Configuration Files:**

   > You'll need to set up a few configuration files for the bot to work properly.

## 📁 Configuration Files

### 1. `configs.json` 📜 - Adjust configuration

```json
{
  "limit": 100,
  "countdown": 300,
  "country_time": "en-US",
  "howManySpeedBoost": 1,
  "howManyCapacityBoost": 1,
  "delayEachAccount": [5, 8],
  "referralCode": "38f044",
  "doTasks": true,
  "playGames": true
}
```

### 2. `datas.txt` 🗂️ - [Get it from here](https://t.me/KeoAirDropFreeNee/1586)


```txt
query_id.../user...
query_id.../user...
query_id.../user...
```

### 3. `wallets.txt` 💼 - Cannot update yet.

- Wallets generator: [Link](https://github.com/MeoMunDep/Automatic-Ultimate-Create-Wallets-for-Airdrop)

```txt - wallet address
abc...xyz
abc...xyz
abc...xyz
```

### 4. `proxies.txt` 🌐 - Proxy is an option. If you have one, fill it in; otherwise, leave it blank.


- [Get it from here](https://www.webshare.io/?referral_code=4l5kb3glsce7)

```txt
http://host:port
https://host:port
socks4://host:port
socks5://host:port
http://user:pass@host:port
https://user:pass@host:port
socks4://user:pass@host:port
socks5://user:pass@host:port
```

💡 Usage:

> You need to `cd` to the file after extract it
> To run the bot, use the following command: `cd pitchtalk-main/pitchtalk; node meomundep`

🎇Enjoy!
