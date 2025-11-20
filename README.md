# spotify-popularity-analysis

# Spotify Şarkı Popülerliği Tahmin Projesi

Bu projede, Spotify veri seti kullanılarak şarkıların popülerlik puanları tahmin edilmeye çalışılmıştır. Analizler Jupyter Notebook üzerinde yapılmış ve bir makine öğrenimi modeli olarak **RandomForestRegressor** kullanılmıştır.

## Proje İçeriği
- **kod.ipynb** → Veri analizi, grafikler ve model eğitimi.
- **Sunum.pdf** → Projenin sunumu.
- **README.md** → Proje özet bilgisi.

## Veri Seti
- Kaynak: TidyTuesday – Spotify Tracks
- Özellikler: danceability, energy, acousticness, loudness, valence, tempo
- Hedef: track_popularity

## Kullanılan Model
- **Random Forest Regressor**
- Amaç: Ses özelliklerine göre popülerlik tahmini yapmak

## Özet Bulgular
- Loudness, acousticness ve energy en önemli değişkenler olarak ortaya çıkmıştır.
- Popülerlik yalnızca ses özelliklerine bağlı olmadığından skor sınırlıdır.

## Not
GitHub bazen `.ipynb` dosyalarını görüntülerken hata verebilir. Notebook indirildiğinde sorunsuz açılır.

---

Proje Sahibi: **Duygu Çimen**
