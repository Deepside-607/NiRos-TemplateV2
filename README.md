# NiRos-TemplateV2
### این تمپلیت برای ربکا نسخه باینری نوشته شده است درصورتی که پنل شما همچنان روی نسخه داکر میباشد این تمپلیت را نصب نکنید از نسخه اول تمپلیت استفاده کنید
![Preview](https://github.com/Deepside-607/NiRos-TemplateV2/blob/main/IMG_20251220_182226.jpg?raw=true)

### ربکا:  
### ابتدا قالب را با لینک زیر دانلود کنید

```bash
sudo wget -N -P /var/lib/rebecca/templates/subscription/ https://raw.githubusercontent.com/Deepside-607/NiRos-TemplateV2/main/index.html
```
### سپس دستور زیر را بزنید تا تمپلیت ست شود

```bash
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/rebecca/templates/"' | sudo tee -a /opt/rebecca/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/rebecca/.env
```

### سپس با دستور زیر پنل خودتون رو ری‌استارت کنید

```bash
rebecca restart
```
