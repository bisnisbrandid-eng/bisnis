# FinanceApp with GitHub Actions

Project ini sudah dilengkapi dengan workflow GitHub Actions untuk build APK otomatis.

## Cara pakai:
1. Upload semua file project ini ke GitHub (repo public/private).
2. Pastikan branch utama bernama `main`.
3. GitHub Actions akan otomatis jalan saat push, atau jalankan manual di tab "Actions".
4. Setelah selesai, APK bisa diunduh di tab "Artifacts" → `app-debug.apk`.

---
> Jika ingin build manual di lokal: jalankan `./gradlew assembleDebug`
