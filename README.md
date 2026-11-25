# JDConverterPDF — Official Desktop Releases

Distribusi resmi installer desktop **JDConverterPDF v1.0.0** (100% Offline PDF, Office & Image Studio) untuk **Windows** dan **Ubuntu Linux**.

🌐 Website Resmi: [https://pdfconvert.jdapps.web.id](https://pdfconvert.jdapps.web.id/)

---

## Unduh Installer (`v1.0.0`)

| Sistem Operasi | Paket Installer | Ukuran | Link Unduhan Langsung |
|---|---|---|---|
| **Windows 10 / 11 (64-bit)** | `JDConverterPDF-Setup-1.0.0.exe` (Inno Setup 6) | ± 178 MB | [Unduh Installer Windows (.exe)](https://github.com/Izza152/PDF_Converter_JDAPPS/releases/latest/download/JDConverterPDF-Setup-1.0.0.exe) |
| **Ubuntu 22.04 / 24.04 LTS (amd64)** | `jdconverterpdf_1.0.0_amd64.deb` (GUI GTK3 + WebKit2GTK) | ± 160 MB | [Unduh Paket Ubuntu (.deb)](https://github.com/Izza152/PDF_Converter_JDAPPS/releases/latest/download/jdconverterpdf_1.0.0_amd64.deb) |

> Distro Linux lainnya (Fedora `.rpm`, Arch `AUR`, AppImage & Flatpak), macOS, dan Android masih dalam pengembangan.

---

## Cara Instalasi Melalui Terminal

### Ubuntu / Debian (`.deb` GUI)

```bash
curl -fLO "https://github.com/Izza152/PDF_Converter_JDAPPS/releases/latest/download/jdconverterpdf_1.0.0_amd64.deb"
sudo apt update
sudo apt install -y ./jdconverterpdf_1.0.0_amd64.deb
jdconverterpdf
```

*(Opsional untuk konversi Word/Excel ke PDF offline jika LibreOffice belum terpasang: `sudo apt install -y libreoffice-writer libreoffice-calc`.)*

### Windows (PowerShell)

```powershell
$installer = "$env:USERPROFILE\Downloads\JDConverterPDF-Setup-1.0.0.exe"
Invoke-WebRequest -Uri "https://github.com/Izza152/PDF_Converter_JDAPPS/releases/latest/download/JDConverterPDF-Setup-1.0.0.exe" -OutFile $installer
Start-Process -FilePath $installer
```

### Windows WSL2 (Ubuntu GUI / WSLg)

```bash
curl -fLO "https://github.com/Izza152/PDF_Converter_JDAPPS/releases/latest/download/jdconverterpdf_1.0.0_amd64.deb"
sudo apt update && sudo apt install -y ./jdconverterpdf_1.0.0_amd64.deb
jdconverterpdf
```

---

## Verifikasi Checksum (SHA-256)

```text
6D93D9E9469CFB285824B68C3F2D796D939791A6AF5E01056D57D383F2A2DD91  JDConverterPDF-Setup-1.0.0.exe
CBD7523796349E2E93ADDBE1B8E04CA6536C1CE3A2847649EF95B62070FDA238  jdconverterpdf_1.0.0_amd64.deb
```
