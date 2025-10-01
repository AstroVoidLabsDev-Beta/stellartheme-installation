# Stellar Theme for Pterodactyl

Stellar is a custom theme for the **Pterodactyl Panel**, designed to give a modern and clean UI experience.

---

## 📥 Installation

Follow these steps to install Stellar Theme on your Pterodactyl panel:

```bash
# 1. Clone the installer repository
git clone https://github.com/AstroVoidLabsDev-Beta/stellartheme-installation

# 2. Enter the folder
cd stellartheme-installation

# 3. Move StellarTheme into your Pterodactyl directory
mv StellarTheme /var/www/pterodactyl

# 4. Go to the Pterodactyl directory
cd /var/www/pterodactyl

# 5. Install required dependencies
yarn add react-feather

# 6. Run migrations (type 'yes' if prompted)
php artisan migrate

# 7. Build assets
yarn build:production

# 8. Clear cached views
php artisan view:clear
```

✅ **Success!** Stellar Theme is now installed on your Pterodactyl panel.  

---

## 👨‍💻 Credits
- **Theme Credit:** ITZ_YTANSH  
- **Code & Guide Credit:** ITZ_YTANSH  
- Updates: Follow [AstroVoidLabsDev-Beta](https://github.com/AstroVoidLabsDev-Beta)  

---

## ⚡ Notes
- Make sure you already have **Node.js, Yarn, and PHP dependencies** installed before running the commands.  
- Always back up your original panel files before applying themes.

---

## 🖼️ Theme Preview


![Stellar Theme Preview](https://builtbybit.com/attachments/1743544778858-png.926694/?preset=fullr1)
