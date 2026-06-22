# My App

Simple app: Input teks → Kirim → Muncul notif.

## Fitur
- Text input
- Kirim pesan
- Local notification muncul
- Daftar pesan tersimpan

## Cara Build

### Otomatis (GitHub Actions)
1. Push kode ke GitHub
2. GitHub Actions otomatis build
3. Download APK dari **Actions** → **Artifacts**

### Manual
```bash
flutter pub get
flutter build apk --release
```

## Cara Coding di HP

### Pakai Termux
```bash
pkg install git
git clone https://github.com/username/my-app.git
cd my-app
flutter pub get
flutter run
```

### Pakai Acode
- Install Acode dari Play Store
- Buka folder project
- Edit file `.dart` di `lib/`

## Struktur Project
```
my-app/
├── lib/main.dart          # Kode utama app
├── android/               # Konfigurasi Android
├── pubspec.yaml           # Dependencies
├── .github/workflows/     # GitHub Actions config
└── README.md              # File ini
```

## Screenshot
(Tambahkan screenshot setelah app jalan)
