# Sonic Agent

### ⚡ Landing Page — Autonomous AI Agents for Your Engineering Workflow

*Demo/prototipe front-end untuk produk Sonic Agent — terhubung ke GitHub, Jira, dan Slack untuk menjalankan CI pipeline, triase issue, dan rilis software secara otonom.*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-orange.svg)](CONTRIBUTING.md)
[![Made with HTML/CSS/JS](https://img.shields.io/badge/stack-HTML%2FCSS%2FJS-FF3C00.svg)](index.html)

---

## 📌 Tentang Proyek Ini

Repo ini adalah **landing page statis** (HTML, CSS, JS — tanpa framework dan
tanpa build step) untuk "Sonic Agent", sebuah konsep produk AI agent untuk
workflow engineering. Halaman ini mencakup:

- Hero section, pricing, FAQ, dan navigasi lengkap ala produk SaaS
- Layar login/register dengan animasi kanvas (simulasi, tidak terhubung ke backend nyata)
- Panel demo "Clone GitHub Repo" yang memanggil GitHub REST API publik
- Widget chat AI (placeholder — lihat catatan di [`SECURITY.md`](SECURITY.md))

> ⚠️ **Ini adalah demo front-end.** Tidak ada server backend sungguhan di
> balik fitur login, clone, atau chat. Lihat [`docs/JAVASCRIPT.md`](docs/JAVASCRIPT.md)
> untuk rincian setiap fitur dan [`SECURITY.md`](SECURITY.md) sebelum
> deploy ke produksi.

---

## 🚀 Quick Start

### Opsi 1 — Buka langsung di browser

Cukup buka file `index.html` di browser apa pun. Tidak ada instalasi yang
diperlukan.

### Opsi 2 — Jalankan lewat local server

```bash
git clone https://github.com/<username-anda>/sonic-agent.git
cd sonic-agent
python3 -m http.server 8000
# buka http://localhost:8000
```

### Opsi 3 — Deploy ke GitHub Pages

Lihat panduan lengkap di [`docs/DEPLOYMENT.md`](docs/DEPLOYMENT.md).

---

## 📚 Struktur Proyek

```
sonic-agent/
├── index.html              # Markup halaman (head, nav, hero, pricing, FAQ, dst.)
├── assets/
│   ├── css/style.css       # Seluruh styling
│   └── js/main.js          # Seluruh logika interaktif
├── docs/
│   ├── STRUCTURE.md        # Penjelasan tata letak file
│   ├── JAVASCRIPT.md       # Penjelasan tiap fungsi di main.js
│   └── DEPLOYMENT.md       # Cara deploy
├── .github/ISSUE_TEMPLATE/ # Template bug report & feature request
├── LICENSE
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
└── SECURITY.md
```

Lihat [`docs/STRUCTURE.md`](docs/STRUCTURE.md) untuk penjelasan lebih detail.

---

## ✨ Fitur Halaman

| Bagian              | Deskripsi                                                        |
| -------------------- | ----------------------------------------------------------------- |
| 🔐 **Login/Register** | Form lengkap dengan validasi, strength meter, dan demo autofill |
| 🧭 **Navigasi**       | Nav bar sticky, scroll-spy, menu hamburger di mobile             |
| 💸 **Pricing**        | Starter (gratis), Pro, Enterprise                                |
| ❓ **FAQ**            | Accordion FAQ                                                    |
| 🐙 **GitHub Clone Demo** | Ambil metadata repo asli via GitHub API + simulasi proses clone |
| 💬 **Chat Widget**    | UI chat siap pakai (perlu backend proxy agar benar-benar membalas) |

---

## 🤝 Berkontribusi

Kontribusi apa pun diterima — dari memperbaiki typo hingga menambah section
baru.

1. **Fork** repo ini
2. **Buat branch**: `git checkout -b feat/fitur-anda`
3. **Commit**: `git commit -m "feat: tambahkan X"`
4. **Push**: `git push origin feat/fitur-anda`
5. **Buka Pull Request**

Baca panduan lengkap di [`CONTRIBUTING.md`](CONTRIBUTING.md).

| Jenis              | Cara                                                          |
| ------------------- | -------------------------------------------------------------- |
| 🐛 Menemukan bug     | [Buka Issue](../../issues/new?template=bug_report.md)         |
| 💡 Ide fitur         | [Buka Issue](../../issues/new?template=feature_request.md)    |
| 📝 Perbaikan konten  | Ajukan Pull Request                                            |

---

## 📄 Lisensi

Dilisensikan di bawah [MIT License](LICENSE).

---

**⭐ Jika proyek ini bermanfaat, beri bintang pada repo ini!**
