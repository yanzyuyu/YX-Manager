# YX Manager

Root-based Android Kernel & Hardware Performance Manager built with Jetpack Compose.

<p align="center">
  <a href="https://github.com/yanzyuyu/YX-Manager/releases/latest"><img src="https://img.shields.io/badge/release-v1.0.1-0969da?logo=github&logoColor=white" alt="Release" /></a>
  <a href="#"><img src="https://img.shields.io/badge/android-8.0%2B%20(API%2026%2B)-3DDC84?logo=android&logoColor=white" alt="Android" /></a>
  <a href="#"><img src="https://img.shields.io/badge/access-root%20(UID%200)-critical" alt="Root Access" /></a>
  <a href="#"><img src="https://img.shields.io/badge/ui-jetpack%20compose-4285F4?logo=jetpackcompose&logoColor=white" alt="UI" /></a>
  <a href="https://saweria.co/Ynzoffc"><img src="https://img.shields.io/badge/donate-saweria-faae2b" alt="Donate" /></a>
</p>

## Fitur Utama

- **Display Engine & Resolution Safety:** Kustomisasi resolusi layar dan densitas DPI (`wm size` & `wm density`), refresh rate controller (60/90/120 Hz), dialog peringatan risiko, serta pratinjau keamanan 5 detik dengan pemulihan otomatis jika salah input.
- **Real-Time CPU Monitor & Core Hotplug:** Pemantauan frekuensi tiap cluster dan core CPU secara live dengan pengaman konfirmasi destruktif saat mematikan physical core.
- **Battery Status & Power Telemetry:** Monitoring arus daya (mA), konsumsi watt (W), tegangan cell (mV), suhu (°C), dan estimasi waktu pengisian/penggunaan secara realtime.
- **Memory & zRAM Manager:** Kontrol swap memory, ukuran zRAM disksize, swappiness, dan optimalisasi alokasi RAM.
- **Boot Partition Flasher:** Flasher partisi boot (mendukung slot A/B) dan AnyKernel3 installer langsung via root shell, lengkap dengan backup & restore boot image.
- **YX Module System (Standalone Hub):** Sistem modul independen berbasis `/data/adb/yx_modules` yang dibuat khusus untuk YX Kernel Manager, mendukung *systemless overlay*, `system.prop`, script boot `service.sh`, dan aksi kustom tanpa bergantung pada manajer modul eksternal.
- **Root-Based Fast Install:** Pembaruan aplikasi instan melalui hak akses root (`pm install -r -d`) dengan dukungan downgrade langsung dari GitHub Releases.

## Unduh Aplikasi

Silakan unduh file APK versi release terbaru pada tab [Releases](https://github.com/yanzyuyu/YX-Manager/releases/latest).

## Dukungan

Dukung pengembangan YX Manager melalui [Saweria](https://saweria.co/Ynzoffc).