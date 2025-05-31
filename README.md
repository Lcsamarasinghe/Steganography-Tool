# 🕵️‍♂️ Steganography Tool

A simple and elegant web-based steganography tool that allows you to **hide and reveal secret messages inside images** using password protection. Built with HTML, CSS, and JavaScript.

![Screenshot](https://github.com/Lcsamarasinghe/Steganography-Tool/blob/450233c7a5c8132e6df3633ce7657911d11231b6/S1.PNG)


![Screenshot](https://github.com/Lcsamarasinghe/Steganography-Tool/blob/450233c7a5c8132e6df3633ce7657911d11231b6/S1.PNG)

---

## 🚀 Features

- 🔐 **Hide messages** in images securely using a password
- 🔍 **Reveal hidden messages** with password verification
- 📷 Supports all standard image formats (PNG, JPG, etc.)
- 👁️ Toggle password visibility
- 🕒 Built-in digital clock
- 🎨 Animated background with responsive UI
- 📥 One-click download of the modified image
- ✅ Lightweight – no server required

---

## 🛠️ How It Works

### 🔐 Hide Message
1. Upload an image.
2. Enter your secret message.
3. Set a password (used to encrypt and later reveal the message).
4. Click **"Hide Message & Download Image"**.
5. The tool embeds the message in the image and downloads it to your device.

### 🔍 Reveal Message
1. Upload the image with the hidden message.
2. Enter the password used when hiding the message.
3. Click **"Reveal Hidden Message"** to display the secret.

---

## 🧠 Technology Used

- HTML5 & CSS3
- JavaScript (Vanilla)
- Canvas API
- Base64 image handling
- Simple hashing for password verification

---

## 📂 File Structure

```bash
├── index.html         # Main web interface
├── style.css          # All embedded in HTML
├── script.js          # All embedded in HTML
└── README.md          # Project documentation
