# Web Sayt - Railway uchun tayyor

Chiroyli, zamonaviy landing page (portfolio / shaxsiy sayt).

## Fayllar
- `index.html` — asosiy sahifa
- `styles.css` — dizayn
- `script.js` — animatsiyalar va smooth scroll

## GitHub ga joylash

```bash
git init
git add .
git commit -m "Web sayt"
git branch -M main
git remote add origin https://github.com/SIZNING_USERNAME/REPO_NOMI.git
git push -u origin main
```

## Railway ga deploy qilish (24/7)

1. https://railway.app ga kiring
2. **New Project** → **Deploy from GitHub repo**
3. O'z reposingizni tanlang
4. Railway avtomatik aniqlaydi

### Start Command (muhim!)
Agar Railway o'zi ishga tushirmasa, Settings → Deploy da quyidagini yozing:

```
npx serve -s . -l $PORT
```

Yoki Python bilan:

```
python -m http.server $PORT
```

### Domain
Railway sizga `xxx.up.railway.app` domain beradi.  
Keyin o'zingizning domeningizni ham ulang (Settings → Domains).

## O'zgartirish
- `index.html` ichidagi matnlarni o'zgartiring
- Telegram linkini o'zingiznikiga almashtiring
- Ranglar `styles.css` da

Tayyor!
