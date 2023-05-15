**📢 This repo is maintained and up to date.**

<sup>(If it ever gets abandoned, this date will be far in the past: <i>May 15, 2023</i> )</sup>

---

# 💌 Send to Hydrus
Share files and URLs on Android into [Hydrus](https://github.com/hydrusnetwork/hydrus) ClientAPI

## 🛠️ Setup
  - Download [HTTP Shortcuts](https://http-shortcuts.rmy.ch/)
  - Under "Import / Export", choose "Import from URL", enter<br>`https://github.com/Wyrrrd/send-to-hydrus/releases/latest/download/shortcuts.zip`
  - On first use, this will ask for your Hydrus ClientAPI URL and walk you through API key generation, but you can also set the variables `hydrus_url` and `hydrus_api_key` manually

## 🔑 Permissions
The API key needs file and URL permissions for this to work its magic.

If you are using the older, URL-only version, your API key will not have the file permission. To fix this, remove the API key in Hydrus and clear the variable `hydrus_api_key`. On next use, this will help you setup a new API key with the correct permissions.

## 🤲 Usage

### Easy way (this is what you are here for)
  - Share the URL or file from whatever menu you normally use, as if you would send it to a friend.
  - Choose "HTTP Shortcuts" from the apps list.
  - ...
  - Profit (?)
  
### Complicated way
  - Open HTTP Shortcuts
  - Press "Send URL" / "Send file"
  - Copy and Paste URL / Choose file to send
  - Press "OK"
  
