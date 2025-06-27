# Dark Web Script for FiveM (NUI-Based)

![Banner](https://i.ibb.co/sJpnn568/rf-scripts-logo-removebg-preview.png)

An immersive, fully NUI-based Dark Web system that brings a realistic underground marketplace into your FiveM server. Inspired by TOR browsing, with rotating black market inventory, delivery locations, and realistic payment collection.

🛒 **Purchase the script here:** [Buy on Tebex](<https://rf-scripts.tebex.io/>)

---

## 📸 Preview

### 💻 Laptop UI
![Laptop Boot](https://i.ibb.co/vvkfD8KB/dw-laptop-ui.png)

### 🕵️‍♂️ TOR Terminal
![Tor Browser](https://i.ibb.co/xtJmxkw1/dw-tor-teminal.png)

### 🕵️‍♂️ TOR Search Engine
![Tor Browser](https://i.ibb.co/hxYGRr5F/dw-tor-search.png)

### 🕵️‍♂️ TOR Search Result
![Tor Browser](https://i.ibb.co/1fszgQyd/dw-search-result.png)

### 🛒 Dark Web Market UI
![Market](https://i.ibb.co/38nrSPr/dw-market-page.png)

### 📦 Delivery Ped Automatic Waypoint
![Market](https://i.ibb.co/rntmVqV/dw-automatic-waypoint.png)

### 📦 Delivery Ped Interaction
![Delivery Ped](https://i.ibb.co/kggKBxTN/dw-ped-waiting.png)
![Delivery Ped](https://i.ibb.co/cX6w11FK/dw-transaction.png)


---

## 📦 Features

- Custom laptop-based UI with NUI integration  
- Emulates TOR browser & dark web black market  
- Items rotate on **every server restart**  
- Requires a specific item to access (e.g., USB)  
- Configurable laptop props for activation  
- Payment collected at the **delivery location**  
- Highly customizable `config.lua`

---

## 🔧 Installation Guide

### 1. Download & Extract

- Purchase and download the ZIP from [Tebex](<https://rf-scripts.tebex.io/>)  
- Extract the files  
- Rename the folder (e.g., `darkweb`)

### 2. Add to Server Resources

Move the script into your server’s `resources` directory:

### 3. Add to server.cfg

Edit your `server.cfg` and add:

---

### 4. Configure the Script

Edit the `config.lua` file to customize key elements:

#### 🛒 Items & Prices

- Define what items are available for sale
- Set the price for each item
- Items rotate on **every server restart**

#### 📦 Delivery System

- Set multiple delivery drop-off points
- After purchase, the player receives a map blip
- Payment is taken by the ped at the delivery site before handing over the item

#### 🔑 Access Requirements

- Set a required item (e.g., USB stick) to use the laptop
- Define which laptop models or props are interactable
- Prevents players from using the dark web unless properly equipped

#### 🖥️ Full Custom NUI

- Laptop login/boot interface
- Realistic dark web navigation
- TOR-style browser/search
- Built-in product pages and checkout experience

---

## 🧪 How It Works (Quick Flow)

1. Player obtains the required access item (e.g., USB)
2. Approaches a compatible laptop prop in the world
3. Uses third-eye interaction to open the NUI interface
4. Navigates the TOR browser to access dark web items
5. Orders an item — a map marker appears for delivery
6. Player travels to the delivery location
7. Interacts with the ped, pays the fee, and receives the item

---

## ⚙️ Summary of Config Options

| Config Option              | Purpose                                             |
|---------------------------|------------------------------------------------------|
| `Config.Items`            | List of dark web items + prices                      |
| `Config.DeliveryLocations`| World coordinates for drop-off points                |
| `Config.RequiredItem`     | Item needed to access the system                     |
| `Config.LaptopProps`      | Models/props that can trigger the laptop interface   |
| `Config.PaymentMethod`    | Payment method at delivery (usually cash)            |

---

## ⚠️ Terms of Use

This script is **created and owned by RF Scripts**. By purchasing or using this script, you agree to the following:

- 🚫 **No Redistribution**  
  You may not re-upload, resell, or share this script.

- 🛡️ **No Cracking or Leaking**  
  Any attempt to crack or leak this resource is strictly prohibited.

- 👤 **Single Server License**  
  Purchase includes usage rights for one server only.

- 📧 **Verified Support Only**  
  Only Tebex-verified customers may access support or updates.

---

## 💬 Support

Need help or want to report a bug? Join our Discord or reach out via our Tebex support page.

Thank you for supporting and respecting independent development!
