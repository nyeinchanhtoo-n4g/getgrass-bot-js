# 🌱 getgrass-miner-bot-js

## GetGrass Season 2 mining

- A Node.js bot script to automate grass Season 2 mining.

# Telegram Channel : [@getgrassbotjs](https://t.me/getgrassbotjs)

## ⛩ Table Release

| Bot Version | Status(Work/Not/(N/A) ) |
|---|---|
| [grass-desktop-v0.2](https://github.com/cmalf/getgrass-bot-js/releases/tag/grass-desktop-v0.2) | Not |
| [getgrass-bot-v0.3](https://github.com/cmalf/getgrass-bot-js/releases/tag/getgrass-bot-v0.3) | Not |
| [getgrass-bot-v0.3.1-minor-update](https://github.com/cmalf/getgrass-bot-js/releases/tag/getgrass-bot-v0.3.1-minor) | Not |
| [getgrass-bot-v0.4](https://github.com/cmalf/getgrass-bot-js/releases/tag/getgrass-script-v0.4-Freemium) | Not ( New Authentication Method ) |
| [getgrass-bot-v0.4.1-Beta](https://github.com/cmalf/getgrass-bot-js/releases/tag/getgrass-script-v0.4.1-Freemium-mu) | N/A ( under development ) |
| [getgrass-bot-v0.4.1-Extension-GM](https://github.com/cmalf/getgrass-bot-js/releases/tag/getgrass-bot-v0.4.1-Extension-GM) | Work ( Extension 1.0x ) |
| [getgrass-bot-v0.4.1-Ext-Multi](https://github.com/cmalf/getgrass-bot-js/releases/tag/getgrass-bot-v0.4.1-Extension-GM) | Work (Multi Account Support ) |
| [getgrass-bot-v0.4.1-Comunity-Extension-1.25x ](https://github.com/cmalf/getgrass-bot-js/releases/tag/getgrass-bot-v0.4.1-Extension-GM) | Work ( Comunity Extension 1.25x ) |
| [getgrass-bot-v0.4.2-Community-Extension-GM-All](https://github.com/cmalf/getgrass-bot-js/releases/tag/getgrass-bot-v0.4.2-GM-ALL) | Work ( Multi & Normal ) |

## 🗣 Discussions

| Discussions | Status(Open/Close/Announcement) |
|---|---|
| [Welcome to getgrass-bot-js Discussions!](https://github.com/cmalf/getgrass-bot-js/discussions/3) | Announcement |
| [Release getgrass-bot-v0.3](https://github.com/cmalf/getgrass-bot-js/discussions/4) | Close |
| [Release getgrass-bot-v0.4-Freemium](https://github.com/cmalf/getgrass-bot-js/discussions/9)| Open |
| [getgrass desktop version (script) 📢❗🚨](https://github.com/cmalf/getgrass-bot-js/discussions/16) | Open ‧₊˚🎄✩ ₊˚🦌⊹♡ |
| [Release ggb-v0.4.2-Community-Extension-GM-All](https://github.com/cmalf/getgrass-bot-js/discussions/18) | Open |

> [!WARNING]
> I am not responsible for any loss or damage caused by this bot. Use it at your own risk.


## 📝 Description

### 🖇️ "Maximize Your Grass Node Mining Profits with This Automated Scripting Bot"

### 🖇️ This Node.js-based JavaScript script automates Grass Node mining, optimizing your earnings by:

- Managing Multiple IP Addresses: Rotates through multiple IP addresses (via proxy) to bypass rate limits and maximize uptime.

- Efficient WebSocket Management: Seamlessly handles WebSocket connections using HTTP/SOCKS protocols for reliable and efficient for mining.

### 🖇️ Ideal for:

- Grass Node miners seeking to streamline their Mining operations
- Users wanting to optimize WebSocket connections, especialy for getgrass node

### 💰 "Take Your Mining to the Next Level: Boost Your Profits Today!" 💸


## 🔓 Register  

- if you don't have a grass account yet, SignUp Here [getgrass.io](https://app.getgrass.io/register/?referralCode=276JtwamaXly4nM)

## 🤔 How To Do

- Check [Release Page](https://github.com/cmalf/getgrass-bot-js/releases) (To downloads The latest version of the bot script ) Or

- Clone This Repo

  - ```bash
    git clone https://github.com/cmalf/getgrass-bot-js.git
    ```
- Go To Folder
  - ```bash
    cd getgrass-bot-js
    ```
- Select the latest version of the bot script

- Install Dependencies
  - ```bash
    npm install
    ```
- Configure All Settings

- Run The Script

  - ```bash
    npm start
    ```

## ⚙️ Configuration

SetUp on `Config.js`

- Get UserId

  - Login to your grass account
  - Go to Dashboard
  - Right Click Open New Tab [get-UserId](https://api.getgrass.io/retrieveUser)

  - Edit Proxy.txt

  - format proxies is: `socks://username:pass@ip:port` Or `http://username:pass@ip:port`
  - Note: `The proxy format depends on the bot version you are using`.

## 📸 ScreenShoot

- Dahsboard

![Screenshot 2024-12-16 at 09 51 03](https://github.com/user-attachments/assets/9e50dc29-4a45-4888-97c9-5b60f62c6594)

- Script
  
![Screenshot 2024-12-16 at 07 27 47](https://github.com/user-attachments/assets/3a4143ec-3bcd-4bd4-8ab6-0d6a8a4e0cd7)

## 📢 Additional information

> [!TIP]
> Proxiesfo is stable again after yesterday's server maintenance (on 2025-01-08) <br>
> so I recommend it again


> [!TIP]
> For this type of websocket connection, the bot relies on speed rather than security. For faster connections, SOCKS5 proxies generally offer better performance than HTTPS proxies. SOCKS5 is protocol agnostic, meaning it can handle all types of traffic, not just HTTP/HTTPS. This flexibility can result in faster speeds, It is recommended to use the socks proxy type. However, for other purposes that rely on security such as webscraping,sensitive activities like online banking, HTTPS proxies is better.

  To get a stable Proxy you can use this Platform, plans ranging from $3 to $125 for 6 months, or use your own choice.
  
- Get Proxies IP address Http and Socks
  - Create an account at [proxies.fo](https://app.proxies.fo/ref/8b1abd0f-c734-1602-5985-612caedf4c7b)
  - Go to `purchase isp`  and `buy` a plan according to `your needs`.
    - You can use `cryptocurrency` for `payment` 
    - <img src="https://github.com/user-attachments/assets/18f24ed1-cfc6-4141-addb-07e009c7226b" width="720" height="480" alt="Screenshot">
  - after that you go to the dashboard `Click Generate proxy Button`
  - Now You can change the Proxy format to :
     - `protocol://username:password@hostname:port`
     - or just look the ss below
     - ![Screenshot 2024-12-06 at 16 24 31](https://github.com/user-attachments/assets/c9d552f1-7241-4705-8580-30a88aae8638)

