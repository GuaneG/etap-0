# Etap 0 — Hava Durumu CLI Aracı

> Data Engineering yol haritamın 0. etabı. Python boşluklarını (set, dosya I/O, modül, venv/pip) kapatmak için yaptığım pekiştirme projesi.

Komut satırından bir şehir adı alıp, o şehrin hava durumunu [Open-Meteo](https://open-meteo.com/en/docs) API'sinden çeken, ekrana basan ve sonucu bir CSV dosyasına kaydeden küçük bir CLI aracı.

## Kullanılan teknolojiler
- **Python 3**
- `requests` — API'ye HTTP isteği
- `argparse` — komut satırı argümanı (hazır gelir)
- `csv` — sonucu CSV'ye yazma (hazır gelir)
- **API:** Open-Meteo (key gerektirmez)

## Kurulum & çalıştırma
```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# Linux/Mac:
source .venv/bin/activate

pip install -r requirements.txt
python hava.py --sehir Istanbul
```

## Örnek çıktı
<!-- TODO: örnek komut çıktısı veya ekran görüntüsü ekle -->

## Öğrendiklerim
<!-- TODO: venv, modül import, try/except, requests akışı hakkında kısa notlar -->

## ✅ Etap 0 Bitiş Kontrol Listesi
- [ ] set ile bir listedeki tekrarları temizleyebiliyorum
- [ ] `with open(...)` ile dosya okuyup yazabiliyorum
- [ ] Kendi modülümü başka dosyadan import edebiliyorum
- [ ] `if __name__ == "__main__":` ne işe yarar açıklayabiliyorum
- [ ] venv kurup aktive edebiliyor, pip ile paket kurabiliyorum
- [ ] requirements.txt'nin neden gerekli olduğunu biliyorum
- [ ] argparse + requests ile bir CLI aracı yazdım ve çalışıyor
