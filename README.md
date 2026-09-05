# Portofolio Nadhea Ameylia

File ini berisi halaman portofolio statis yang dapat diakses lokal atau dideploy ke GitHub Pages.

Cara menjalankan secara lokal:

```bash
cd "c:/Users/Nadhea/Downloads/portofolio"
python -m http.server 8000
# lalu buka http://localhost:8000/index.html
```

Cara deploy ke GitHub Pages (singkat):

```bash
git init
git add .
git commit -m "Add portfolio site"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
# lalu aktifkan GitHub Pages dari branch `main` di pengaturan repo
```

Ganti `<username>` dan `<repo>` sesuai akun GitHub Anda (mis. `deamey1305/portfolio`).
