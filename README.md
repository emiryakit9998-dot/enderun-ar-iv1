# Enderun Arşiv

Internet Archive esintili, mavi-beyaz müze estetiğine sahip Node.js arşiv sitesi.

## Özellikler
- Kullanıcı hesabı ve giriş
- Normal kullanıcı / moderatör rolleri
- Kategoriler
- Dosya yükleme ve indirme
- Moderatör için silme yetkisi
- SQLite + kalıcı DATA_DIR

## Çalıştırma
```bash
npm install
npm start
```
Sonra http://localhost:3000

## İlk moderatör
Sunucuyu ilk kez başlatmadan önce ortam değişkenleri ver:
- MOD_EMAIL=moderator@example.com
- MOD_PASSWORD=guclu-bir-sifre

Örnek:
```bash
MOD_EMAIL=admin@example.com MOD_PASSWORD=degistir npm start
```

## Kalıcı depolama
Hosting'de kalıcı disk/volume'u `/data` konumuna bağla ve `DATA_DIR=/data` ayarla.
