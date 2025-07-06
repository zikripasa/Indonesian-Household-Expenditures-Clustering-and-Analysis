# Indonesian-Household-Expenditures-Clustering-and-Analysis

## Project Overview

This project focuses on analyzing Indonesian household expenditure data, a critical economic indicator contributing approximately 70% to the nation's GDP. Understanding these expenditure patterns is vital for assessing economic well-being, poverty levels, and income distribution. Despite significant economic progress, Indonesia faces persistent challenges with economic inequality, evident in disparities across regions and social groups. This project aims to leverage household expenditure data to identify distinct socio-economic segments, enabling more targeted and effective policy interventions to reduce poverty and inequality.

## Raw Dataset Link

File pengeluaran.csv pada link berikut: 
[https://www.kaggle.com/datasets/wowevan/dataset-kesejahteraan-pekerja-indonesia/data](https://www.kaggle.com/datasets/wowevan/dataset-kesejahteraan-pekerja-indonesia/data)

## Insight & Findings

Hasil Clustering dan Analysis Data Pengeluaran Masyarakat di Indonesia menghasilkan **insight** dan **temuan** sebagai berikut:

---

### **CLUSTER 0**

**Rata-rata Pengeluaran**: Rp 543.800,16
**Rentang Pengeluaran**: Rp 488.224,33 – Rp 600.794,13
**Variasi Pengeluaran**: Rp 281.523,23 (Rp 272.916,74 – Rp 291.981,36)

**Daftar Lengkap Provinsi (15)**: ACEH, BANTEN, DI YOGYAKARTA, INDONESIA, JAMBI, JAWA BARAT, JAWA TIMUR, KALIMANTAN SELATAN, NUSA TENGGARA BARAT, SULAWESI SELATAN, SULAWESI TENGAH, SULAWESI UTARA, SUMATERA BARAT, SUMATERA SELATAN, SUMATERA UTARA

**Karakteristik**:
Cluster ini merepresentasikan kelompok masyarakat dengan **pengeluaran menengah**. Daya beli pada kelompok ini relatif sedang, dan cocok dikategorikan sebagai masyarakat **kelas menengah** dengan stabilitas ekonomi yang cukup baik, meskipun terdapat variasi pengeluaran yang mengindikasikan perbedaan kebutuhan atau pola konsumsi antar wilayah/individu. Hal ini menjadikan kelompok ini ideal untuk **pengembangan industri kecil dan menengah (IKM)**.

---

### **CLUSTER 1**

**Rata-rata Pengeluaran**: Rp 646.157,16
**Rentang Pengeluaran**: Rp 586.568,56 – Rp 859.616,64
**Variasi Pengeluaran**: Rp 289.238,49 (Rp 278.379,08 – Rp 300.426,21)

**Daftar Lengkap Provinsi (9)**: BALI, DKI JAKARTA, KALIMANTAN TENGAH, KALIMANTAN TIMUR, KEP. BANGKA BELITUNG, KEP. RIAU, PAPUA, PAPUA BARAT, RIAU

**Karakteristik**:
Menempati posisi kedua tertinggi dalam hal pengeluaran, cluster ini tergolong masyarakat dengan **daya beli tinggi**. Rata-rata pengeluaran yang besar dan rentang maksimum yang jauh lebih tinggi dibanding cluster lain menunjukkan kekuatan ekonomi yang signifikan. Variasi pengeluaran yang cukup besar mencerminkan perbedaan gaya hidup atau kondisi ekonomi di antara anggotanya, kemungkinan besar mencerminkan wilayah-wilayah **urban** atau masyarakat dengan **ekonomi atas**. Untuk kelompok ini, fokus pengembangan dapat diarahkan pada **Usaha Mikro, Kecil, dan Menengah (UMKM)** yang inovatif dan **pelatihan keterampilan** tingkat lanjut.

---

### **CLUSTER 2**

**Rata-rata Pengeluaran**: Rp 495.922,56
**Rentang Pengeluaran**: Rp 430.750,72 – Rp 537.598,79
**Variasi Pengeluaran**: Rp 263.826,75 (Rp 248.694,18 – Rp 273.114,85)

**Daftar Lengkap Provinsi (10)**: BENGKULU, GORONTALO, JAWA TENGAH, KALIMANTAN BARAT, LAMPUNG, MALUKU, MALUKU UTARA, NUSA TENGGARA TIMUR, SULAWESI BARAT, SULAWESI TENGGARA

**Karakteristik**:
Cluster ini berada di bawah rata-rata nasional (dibanding cluster lain), dengan pengeluaran yang tergolong **rendah-menengah**. Variasi pengeluaran yang tidak terlalu besar mengindikasikan homogenitas relatif di antara anggotanya, kemungkinan besar berasal dari wilayah **semi-urban** atau **rural**. Kelompok ini cocok dikategorikan sebagai masyarakat ekonomi bawah ke menengah yang stabil. **Program bantuan sosial** dan **subsidi** menjadi prioritas utama untuk meningkatkan kesejahteraan kelompok ini.

---

### **CLUSTER 3**

**Rata-rata Pengeluaran**: Rp 776.302,22
**Rentang Pengeluaran**: Rp 776.302,22 – Rp 776.302,22
**Variasi Pengeluaran**: Rp 233.257,11 (Rp 233.257,11 – Rp 233.257,11)

**Daftar Lengkap Provinsi (1)**: KALIMANTAN UTARA

**Karakteristik**:
Cluster ini merupakan kelompok terkecil, namun memiliki rata-rata pengeluaran **tertinggi**. Rentang dan variasi pengeluarannya yang konstan menunjukkan pola belanja yang identik di seluruh anggotanya. Hal ini kemungkinan besar merepresentasikan kelompok khusus seperti **daerah industri, kompleks elit, atau data *outlier***. Konsistensi daya beli tinggi ini dapat diasosiasikan dengan kelompok **premium/elit**, dan memiliki potensi besar untuk **pengembangan sektor jasa** dan **ekonomi digital**.

---

## Conclusion & Recommendation

### Conclusion

Proyek klasterisasi dan analisis data pengeluaran rumah tangga di Indonesia ini berhasil mengidentifikasi empat segmen sosio-ekonomi yang berbeda, masing-masing dengan karakteristik pengeluaran yang unik. Klaster 0 merepresentasikan **kelas menengah** dengan pengeluaran moderat, Klaster 1 mencerminkan kelompok dengan **daya beli tinggi** yang cenderung urban, Klaster 2 adalah kelompok **berpenghasilan rendah-menengah** yang lebih homogen dan tersebar di area semi-urban/rural, dan Klaster 3 mewakili kelompok **premium/elit** dengan pengeluaran yang sangat tinggi dan konsisten, meskipun kecil secara demografi. Temuan ini menegaskan adanya disparitas ekonomi yang signifikan antar wilayah dan kelompok masyarakat di Indonesia. Memahami profil setiap klaster ini krusial untuk perancangan kebijakan ekonomi yang lebih **tepat sasaran dan efektif** dalam mengatasi isu kesenjangan dan kemiskinan.

---

### Recommendation

Berdasarkan hasil analisis klaster, berikut adalah beberapa rekomendasi konkret dan *actionable* yang dapat diterapkan:

1.  **Untuk Klaster 0 (Masyarakat Menengah)**:
    * **Fokus:** Pengembangan **Industri Kecil dan Menengah (IKM)**.
    * **Tindakan:** Pemerintah dan sektor swasta dapat menyediakan akses permodalan yang lebih mudah, pelatihan keterampilan kewirausahaan, serta fasilitasi pemasaran produk IKM untuk meningkatkan daya saing dan stabilitas ekonomi kelompok ini.

2.  **Untuk Klaster 1 (Masyarakat Berdaya Beli Tinggi)**:
    * **Fokus:** Pengembangan **UMKM Inovatif dan Pelatihan Keterampilan Tingkat Lanjut**.
    * **Tindakan:** Mendorong investasi pada sektor jasa bernilai tambah tinggi, ekonomi kreatif, dan teknologi. Menyediakan program pelatihan yang relevan dengan kebutuhan pasar tenaga kerja modern (misalnya, *digital skills, coding, data science*) untuk meningkatkan produktivitas dan pendapatan.

3.  **Untuk Klaster 2 (Masyarakat Rendah-Menengah)**:
    * **Fokus:** Prioritas **Program Bantuan Sosial dan Subsidi**.
    * **Tindakan:** Mengimplementasikan program bantuan sosial yang lebih terarah dan inklusif (misalnya, subsidi pangan, bantuan tunai langsung, program kesehatan gratis) untuk menjaga stabilitas daya beli dan mencegah mereka jatuh ke dalam kemiskinan ekstrem. Peningkatan akses terhadap pendidikan dasar dan kesehatan juga krusial.

4.  **Untuk Klaster 3 (Masyarakat Premium/Elit)**:
    * **Fokus:** Potensi Pengembangan **Sektor Jasa dan Ekonomi Digital**.
    * **Tindakan:** Mengidentifikasi peluang investasi dalam sektor pariwisata premium, properti mewah, layanan keuangan, dan infrastruktur digital. Kebijakan yang mendukung inovasi dan investasi di bidang ini dapat menarik lebih banyak pelaku ekonomi berdaya beli tinggi.

Dengan menerapkan rekomendasi yang disesuaikan dengan karakteristik masing-masing klaster, diharapkan kebijakan pemerintah dapat lebih efektif dalam mencapai tujuan pembangunan ekonomi yang **inklusif dan berkelanjutan**, serta mengurangi kesenjangan ekonomi di Indonesia.

---

## AI Support Explanation

Dalam proyek *capstone* ini, yang merupakan bagian dari program **Data Classification and Summarization using IBM Granite**, pemanfaatan kecerdasan buatan (AI) memainkan peran krusial dalam melakukan analisis data pengeluaran rumah tangga di Indonesia. Proses eksplorasi dan pra-pemrosesan data dilakukan secara komprehensif menggunakan lingkungan **Google Colaboratory**, yang menyediakan akses ke beragam pustaka Python seperti Pandas, NumPy, dan Scikit-learn.

Untuk tugas klasifikasi dan klasterisasi yang menjadi inti dari proyek ini, kami memanfaatkan kapabilitas AI yang canggih dari **IBM watsonx**. Secara spesifik, model kami dikembangkan dan dilatih menggunakan **IBM watsonx.ai** sebagai platform utama untuk membangun, melatih, dan menyebarkan model AI. Dalam lingkungan watsonx.ai, kami mengintegrasikan model klasterisasi yang dibangun. Untuk klasterisasi data pengeluaran rumah tangga, kami mengimplementasikan algoritma **K-Means Clustering**, yang merupakan bagian integral dari pustaka Machine Learning yang tersedia di watsonx.ai. Algoritma ini memungkinkan kami untuk secara efektif mengidentifikasi dan mengelompokkan pola pengeluaran yang berbeda ke dalam segmen-segmen yang jelas, seperti yang terlihat pada hasil klaster 0 hingga 3.

Lebih lanjut, sejalan dengan fokus program pada klasifikasi dan summarisasi data, kami juga memanfaatkan kemampuan **Large Language Model (LLM)** yang tersedia di **IBM watsonx.ai**, khususnya melalui model dasar dari keluarga **IBM Granite**. Meskipun proyek ini berfokus pada klasterisasi numerik, konsep klasifikasi dan summarisasi diterapkan pada tahap interpretasi hasil. Misalnya, setelah klaster terbentuk, kami menggunakan LLM untuk membantu dalam **klasifikasi karakteristik** setiap klaster berdasarkan atribut-atribut data yang dominan, serta untuk **mensumarisasi poin-poin kunci** dari setiap klaster menjadi narasi yang ringkas dan mudah dipahami. Hal ini membantu dalam menyusun "Karakteristik" dan "Rekomendasi" untuk setiap klaster.

Selain itu, untuk manajemen data yang efisien dan skalabel, kami memanfaatkan **IBM watsonx.data** sebagai *data store* yang fleksibel, memastikan akses data yang lancar untuk pelatihan model. Integrasi dengan **IBM watsonx.governance** juga memastikan bahwa seluruh proses pengembangan dan *deployment* model AI mematuhi prinsip-prinsip etika dan transparansi, serta memungkinkan pemantauan kinerja model secara berkelanjutan. Dukungan AI dari ekosistem IBM watsonx ini tidak hanya mempercepat proses analisis, tetapi juga meningkatkan akurasi dan kedalaman *insight* yang dihasilkan dari data pengeluaran rumah tangga, yang pada akhirnya sangat penting untuk perumusan kebijakan yang lebih tepat sasaran.

---
