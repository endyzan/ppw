# Tugas 1 | Pengantar Web Mining



## 1. Pendahuluan

Di era digital saat ini, internet bukan lagi sekadar media komunikasi, melainkan juga gudang data raksasa yang terus bertambah setiap detik. Jutaan website aktif menyimpan informasi dalam berbagai bentuk: teks, gambar, video, maupun data terstruktur. Namun, besarnya volume data web justru menimbulkan tantangan baru: bagaimana cara menggali pengetahuan yang bermanfaat dari lautan data tersebut? Di sinilah **Web Mining** berperan.

**Web Mining** atau penambangan web adalah cabang dari data mining yang secara khusus berfokus pada ekstraksi informasi, penemuan pola, dan penggalian pengetahuan dari data berbasis web. Konsep ini menggabungkan berbagai disiplin ilmu seperti *machine learning, natural language processing, database systems,* dan *analisis jaringan sosial*. Hasil dari Web Mining dapat dimanfaatkan untuk berbagai tujuan, mulai dari sistem rekomendasi produk, analisis perilaku pengguna, deteksi tren, hingga optimasi mesin pencari.



## 2. Definisi Web Mining

Secara sederhana, Web Mining dapat didefinisikan sebagai proses **menemukan pola dan pengetahuan yang tersembunyi dari data web**.  

- Menurut *Etzioni (1996)*: Web Mining adalah penggunaan teknik penambangan data untuk secara otomatis menemukan serta mengekstrak informasi dari layanan web.  
- Menurut *Bing Liu (2007)*: tujuan utama Web Mining adalah menemukan pola berguna dari **struktur hyperlink, isi halaman web, dan perilaku pengguna**.  

Dengan kata lain, Web Mining tidak hanya sekadar membaca data web, tetapi juga memahami **makna, keterkaitan, dan tren** yang terkandung di dalamnya.



## 3. Tantangan dalam Web Mining

Meskipun potensinya besar, Web Mining menghadapi banyak tantangan:  

- **Skala Data yang Besar** – Web berisi miliaran halaman dan terus berkembang setiap saat.  
- **Format Data yang Beragam** – Data tersedia dalam bentuk HTML, XML, teks bebas, gambar, audio, hingga video.  
- **Kompleksitas dan Dinamika** – Struktur web sangat kompleks dan sifatnya dinamis, karena konten bisa berubah sewaktu-waktu.  
- **Tidak Spesifik** – Web mencakup semua domain pengetahuan, sehingga proses mining sering kali memerlukan fokus domain tertentu.  

Karena itulah, dibutuhkan teknik pengolahan data yang cerdas, fleksibel, dan efisien agar hasil Web Mining benar-benar bermanfaat.



## 4. Taksonomi Web Mining

![Taksonomi](./_static/taksonomi.png)

Secara garis besar, Web Mining terbagi menjadi tiga bidang utama:  

### 🔹 Web Content Mining
- **Fokus**: konten halaman web.  
- **Bentuk data**: teks, gambar, audio, video, tabel, atau metadata.  
- **Aplikasi**: *text mining* untuk klasifikasi dokumen, analisis sentimen, ekstraksi kata kunci, hingga rekomendasi berbasis konten.  

### 🔹 Web Structure Mining
- **Fokus**: struktur hyperlink dan keterkaitan antarhalaman.  
- **Tujuan**: menemukan otoritas halaman (contoh: PageRank Google), deteksi komunitas dalam jaringan sosial, atau analisis hubungan antar pengguna.  

### 🔹 Web Usage Mining
- **Fokus**: perilaku pengguna saat berinteraksi dengan website.  
- **Data**: log server, clickstream, cookie, metadata akses.  
- **Aplikasi**: personalisasi layanan, sistem rekomendasi produk, prediksi perilaku pengguna, optimasi desain website.  

Ketiga bidang ini saling melengkapi. Misalnya, konten dapat digali untuk menemukan topik, struktur untuk mengetahui hubungan antar sumber, dan penggunaan untuk memahami preferensi pengguna.



## 5. Proses Web Mining

![Taksonomi](./_static/proseswebmining.png)

Seperti halnya data mining, Web Mining juga melalui beberapa tahapan utama: 

### 🔸 Data Gathering & Exploration
- Mengumpulkan data dari web dengan *web crawling* atau API.  
- Mengeksplorasi data untuk memahami karakteristik awalnya.  

### 🔸 Preprocessing & Transformation
- Membersihkan data dari noise.  
- Transformasi teks menjadi vektor atau embedding.  
- Seleksi fitur, reduksi dimensi, dan integrasi sumber data.  
- Tahap ini biasanya memakan **70–80% waktu proyek** karena persiapan data menentukan kualitas model.  

### 🔸 Actual Data Mining
- Menerapkan algoritma *machine learning* (supervised, unsupervised, atau deep learning).  
- Menghasilkan model, pola, atau pengetahuan dari data.  

### 🔸 Evaluation & Deployment
- Mengevaluasi kualitas model dengan metrik tertentu.  
- Mengimplementasikan hasil ke sistem nyata seperti mesin rekomendasi, search engine, atau dashboard analitik.  



## 6. Contoh Aplikasi Nyata

Beberapa contoh penerapan Web Mining dalam kehidupan sehari-hari:  

- **Google Search** → menggunakan algoritma *PageRank* (Web Structure Mining).  
- **Sistem Rekomendasi E-Commerce** (Tokopedia, Shopee, Amazon) → menganalisis clickstream dan pola belanja (Web Usage Mining).  
- **Analisis Sentimen Media Sosial** → memantau opini publik terhadap isu tertentu (Web Content Mining).  
- **Deteksi Komunitas di Jaringan Sosial** → memetakan kelompok pengguna dengan interaksi intensif (Web Structure Mining).  



## 7. Penutup

Web Mining adalah jembatan antara data masif di internet dengan kebutuhan informasi yang lebih bermakna. Dengan memahami konten, struktur, dan pola penggunaan web, para peneliti maupun praktisi dapat menghadirkan solusi cerdas dalam berbagai bidang seperti bisnis, pemerintahan, pendidikan, maupun kesehatan.  

Seiring perkembangan teknologi seperti **big data, machine learning, dan artificial intelligence**, peran Web Mining akan semakin krusial dalam mengubah data mentah menjadi pengetahuan yang bernilai.  

> Singkatnya, Web Mining adalah *“mata”* yang membantu kita melihat pola tersembunyi di balik layar internet, sehingga informasi yang tersebar bisa terorganisir menjadi wawasan yang berguna.
