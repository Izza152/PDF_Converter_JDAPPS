# JDConverterPDF — Official Desktop Releases

Distribusi resmi installer desktop **JDConverterPDF v1.0.0** (100% Offline PDF, Office & Image Studio) untuk **Windows** dan **Ubuntu Linux**.

🌐 Website Resmi: [https://pdfconvert.jdapps.web.id](https://pdfconvert.jdapps.web.id/)

---

## Unduh Installer (`v1.0.0`)

| Sistem Operasi | Paket Installer | Ukuran | Link Unduhan Langsung |
|---|---|---|---|
| **Windows 10 / 11 (64-bit)** | `JDConverterPDF-Setup-1.0.0.exe` (Inno Setup 6) | ± 175 MB | [Unduh Installer Windows (.exe)](https://github.com/Izza152/PDF_Converter_JDAPPS/releases/latest/download/JDConverterPDF-Setup-1.0.0.exe) |
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
C9E824B3F2E6B617300B64E62DB291E99D1D71B6EFC35E6AB17772F756AED333  JDConverterPDF-Setup-1.0.0.exe
8F32902E4F16CEC47090B6AC265F1A22D27014C4D3E770C041C95CD29B599247  jdconverterpdf_1.0.0_amd64.deb
```
