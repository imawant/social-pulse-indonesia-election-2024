# Analisis Sentimen Pilpres Indonesia 2024
Ini adalah proyek analisis sentimen untuk pemilihan presiden Indonesia 2024. Tujuannya adalah untuk menganalisis dan membuat model prediksi sentimen publik di media sosial terhadap kandidat presiden.

Tentang Proyek
Menjelang pemilihan presiden Indonesia 2024, proyek ini memanfaatkan data Twitter untuk melakukan analisis sentimen dan mengidentifikasi sentimen publik menjelang pemilu. Secara khusus, berfokus pada hal-hal berikut:
- Mengumpulkan tweet terkait kandidat presiden
- Melakukan analisis sentimen untuk mengklasifikasikan tweet sebagai positif, negatif, atau netral
- Membandingkan sentimen antar kandidat untuk memperkirakan popularitas relatif
- Tujuannya adalah untuk kuantifikasi dan melacak pergeseran opini publik Indonesia di media sosial selama siklus pemilu.

Metode yang Digunakan
- Pengumpulan Tweet : Tweet Harvest, Periode : 2023-01-11 sampai 2023-11-23
- Analisis Sentimen Yang dilakukan :
  - Preprocessing Data (Normalisasi REGEX, Slang Words Replacement)
  - Exploratory Data Analysis (visualisasi jumlah sentimen antar paslon, wordcloud sentimen tiap paslon)
  - Modeling (indobert-base, indobertweet, indobert-large-p2)
