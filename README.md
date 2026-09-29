# Bactuary

Actuarial Closing Data Platform; Excel tabanlı hasar/ödeme verisi modelleme ve Power Query dönüşüm katmanı.

## İçerik

- `actuarydatacreating/Actuarial_Closing_Platform.xlsx`: ana Excel çalışma kitabı.
- `actuarydatacreating/PowerQuery_M/`: bağımlılık sırasındaki 28 Power Query sorgusu.
- `actuarydatacreating/PowerQuery_M/ALL_QUERIES.txt`: sorguların tek dosyalık yedeği.
- `actuarydatacreating/datacreating.py`: örnek ödeme listeleri oluşturan Python betiği.
- `docs/`: tüm dosyaları indirmeye yarayan GitHub Pages web sayfası.

## Hızlı başlangıç

1. `Actuarial_Closing_Platform.xlsx` dosyasını Excel ile açın.
2. `Parameters` sayfasındaki kaynak klasörünü ve dönem değerlerini güncelleyin.
3. `Data > Refresh All` ile sorguları ve model çıktısını yenileyin.

Örnek veri üretmek için Python ortamında `pandas`, `numpy` ve `openpyxl` kurulu olmalı; ardından `python actuarydatacreating/datacreating.py` çalıştırılabilir.

## Web sayfası

`main` dalına yapılan her push, `docs/` klasörünü GitHub Pages üzerinden otomatik yayınlar. GitHub deposunda **Settings > Pages > Source: GitHub Actions** seçili olmalıdır.