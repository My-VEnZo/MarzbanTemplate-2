<h1 align="center">🎨 تمپلیت برای پنل <a href="https://github.com/Gozargah/Marzban" target="_blank">مرزبان</a></h1>

<p align="center">
  <img src="https://raw.githubusercontent.com/My-VEnZo/MarzbanTemplate-2/refs/heads/main/template.png" alt="Marzban Template" style="width: 100%; height: auto;">
</p>

<hr>

## 📖 مقدمه  
این تمپلیت برای <strong>مرزبان</strong> طراحی شده و به‌راحتی قابل نصب و استفاده است.

<hr>

## ⚙️ نصب  

برای نصب تمپلیت، مراحل زیر را انجام دهید:

### 1. دانلود فایل تمپلیت:
```bash
sudo wget -N -P /var/lib/marzban/templates/subscription/ https://raw.githubusercontent.com/My-VEnZo/MarzbanTemplate-2/main/index.html
```

### 2. افزودن تنظیمات مسیر به فایل `.env`:
```bash
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"' | sudo tee -a /opt/marzban/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/marzban/.env
```

### 3. ریستارت مرزبان:
```bash
marzban restart
```

<hr>

## 🙏 تشکر  
