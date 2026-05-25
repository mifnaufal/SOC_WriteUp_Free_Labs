# Pendahuluan
Anda telah mempelajari tentang peran analis SOC L1 di ruang Intro Junior Security Analyst. Tetapi di mana posisi tersebut berada dalam struktur perusahaan? Siapa yang mengawasi tim Anda? Departemen keamanan lain apa yang ada? Keterampilan apa yang Anda butuhkan untuk naik dalam jenjang karier? Mari kita cari tahu!

## Tujuan Pembelajaran
- Memahami konsep dan tujuan Blue Team
- Menjelajahi posisi SOC dalam struktur perusahaan
- Mengetahui jalur karier Anda sebagai analis SOC L1

# Hierarki Keamanan
Prioritas keamanan siber berbeda untuk setiap perusahaan. Bagi firma hukum, tujuannya adalah privasi dokumen hukum. Bagi pabrik, ketersediaan jalur produksi. Bagi rumah sakit, keselamatan pasien. Itulah sebabnya setiap perusahaan memiliki pendekatan keamanan dan struktur tim keamanan yang unik. Mari kita lihat contoh tingkat tinggi berikut:
![thm source](https://tryhackme-images.s3.amazonaws.com/user-uploads/678ecc92c80aa206339f0f23/room-content/678ecc92c80aa206339f0f23-1756329066210.png)

Melihat diagram di atas, eksekutif tingkat atas seperti CEO biasanya berfokus pada tujuan bisnis secara global dan tidak mengelola aspek teknis. Oleh karena itu, mereka merekrut seorang Chief Information Security Officer (CISO) atau peran serupa yang memahami kebutuhan bisnis dan dapat membentuk departemen keamanan yang paling sesuai.

## Departemen Keamanan
Di perusahaan yang sangat kecil, departemen IT mengambil peran dalam mengamankan perusahaan. Perusahaan kecil hingga menengah mungkin memiliki tim “Information Security” umum yang menangani berbagai macam tugas. Untuk materi ini, kita akan berfokus pada perusahaan yang lebih besar dengan seorang CISO yang mengawasi beberapa tim keamanan, masing-masing menangani tugas tertentu. Contohnya:

- Red Team: Ahli keamanan ofensif, pentester, atau ethical hacker yang mencari celah keamanan
- Tim GRC: Spesialis yang mengelola kebijakan dan memastikan kepatuhan terhadap regulasi seperti PCI DSS
- Blue Team: Ahli keamanan defensif seperti analis SOC, engineer, atau incident responder

Answer the questions below

**Which senior role typically makes key cyber security decisions?**
```
CISO
```

**What is the common name for roles like SOC analysts and engineers?**
```
Blue Team
```

# Mengenal Blue Team
Blue Team berfokus pada keamanan defensif, yang berarti mereka terus memantau serangan dan berusaha meresponsnya dengan cepat. Bergantung pada ukuran dan sektor perusahaan, Blue Team dapat mencakup banyak peran dan subdepartemen yang berbeda, biasanya berjumlah total 3 hingga 50 anggota. Sekarang, mari kita jelajahi departemen Blue Team yang paling umum.

## Security Operations Center (SOC)
![sumber thm](https://tryhackme-images.s3.amazonaws.com/user-uploads/678ecc92c80aa206339f0f23/room-content/678ecc92c80aa206339f0f23-1756425129235.svg)

Di sinilah kemungkinan besar Anda akan memulai perjalanan keamanan siber Anda! SOC adalah pusat utama keamanan siber sebuah organisasi — mereka merupakan garis pertahanan pertama, bekerja dengan berbagai peringatan, dan menangani sebagian besar serangan. Anda dapat membaca lebih lanjut tentang struktur SOC di ruangan ini, tetapi SOC yang efisien biasanya terdiri dari peran-peran berikut:

- **Analis L1**: Anggota junior yang melakukan triase terhadap peringatan dan meneruskan kasus kompleks ke L2
- **Analis L2**: Anggota berpengalaman yang menyelidiki serangan yang lebih canggih
- **Engineer**: Ahli dalam mengonfigurasi alat keamanan seperti EDR atau SIEM
- **Manager**: Orang yang mengelola seluruh tim SOC

## Cyber Incident Response Team (CIRT)
![sumber thm](https://tryhackme-images.s3.amazonaws.com/user-uploads/678ecc92c80aa206339f0f23/room-content/678ecc92c80aa206339f0f23-1756425129228.svg)

Jika keahlian SOC tidak cukup atau insiden menjadi tidak terkendali, Anda segera memanggil “pemadam kebakaran” — CIRT, yang juga disebut CSIRT atau CERT. Para anggotanya harus memiliki pengetahuan luas tentang ancaman siber dan menangani pelanggaran tanpa bergantung pada alat seperti EDR atau SIEM. Pekerjaan CIRT penuh tekanan dan tanggung jawab, tetapi juga memberikan kepuasan. Berikut beberapa contoh CIRT:

- JPCERT(buka di tab baru): CERT Jepang yang menangani pelanggaran berskala nasional
- Mandiant(buka di tab baru): Tim swasta yang merespons insiden siber global
- AWS CIRT(buka di tab baru): Menyelidiki insiden keamanan pelanggan AWS

## Peran Defensif Khusus
![](https://tryhackme-images.s3.amazonaws.com/user-uploads/678ecc92c80aa206339f0f23/room-content/678ecc92c80aa206339f0f23-1756425129074.svg)

Perusahaan besar, startup yang berfokus pada teknologi, dan lembaga pemerintah sering membutuhkan peran Blue Team yang sempit dan sangat khusus — menarik dan sangat bernilai, tetapi memerlukan pengetahuan mendalam tentang topik tertentu serta pengalaman luas di bidang yang lebih umum seperti SOC atau TI. Peran khusus ini dapat mencakup:

- **Analis Forensik Digital**: Mengungkap ancaman tersembunyi di disk dan memori
- **Analis Intelijen Ancaman**: Mengumpulkan data tentang kelompok ancaman yang sedang berkembang
- **Engineer AppSec**: Menjaga siklus hidup pengembangan perangkat lunak yang aman
- **Peneliti AI**: Mempelajari ancaman AI dan cara mempertahankannya

Answer the questions below

**Does Blue Team focus on defensive or offensive security?**
```
Defensive
```

**Which department handles active or urgent cyber incidents?**
```
CIRT
```

# Memajukan Karier SOC
## Jalur SOC
Memulai sebagai analis SOC L1 bisa menjadi pilihan yang sangat baik untuk memperluas wawasan dunia siber Anda dan memahami peran-peran yang lebih spesifik dengan lebih baik. Selain itu, bahkan peran SOC L1 tingkat pemula pun bisa menyenangkan dan menarik: Anda akan menghadapi serangan nyata, melindungi perusahaan dari kelompok ancaman tingkat lanjut, dan belajar banyak selama proses tersebut. Mari lihat bagaimana Anda bisa memulainya:

1. Kuasai keterampilan inti SOC dan latih terus. Keterampilan terkait seperti red teaming atau IT umum juga akan membantu!
2. Bersikap proaktif, coba ikuti CTF, terus ikuti berita dunia siber, dan pertimbangkan sertifikasi SAL1!
3. Persiapkan diri untuk wawancara, pelajari perbedaan antara SOC internal dan MSSP, lalu lamar pekerjaan!
4. Setelah bekerja beberapa waktu di posisi junior, pertimbangkan untuk mempersiapkan diri dan naik ke peran yang lebih senior!

## SOC Internal vs MSSP

Tidak semua organisasi memiliki keahlian untuk mengoperasikan SOC sendiri dan mengandalkan Managed Security Services Provider (MSSP), yaitu perusahaan yang menyediakan layanan keamanan outsourcing, paling umum SOC, kepada kliennya. Bekerja di MSSP biasanya memiliki tekanan tinggi, tetapi juga merupakan pilihan yang baik untuk memulai karier dengan cepat. Walaupun kami merekomendasikan melamar posisi SOC terbuka apa pun sebagai pekerjaan pertama Anda, penting juga untuk memahami perbedaannya:

| Topik | SOC Internal | MSSP |
|---|---|---|
| **Contoh Skenario** | Anda bekerja di tim SOC sebuah bank dan melindungi sistem bank tersebut | Anda bekerja untuk MSSP global yang melindungi enam puluh pelanggan di Eropa |
| **Tempo Kerja** | Biasanya Anda memiliki shift yang cukup tenang tanpa terlalu banyak tekanan waktu | Shift Anda biasanya dimulai dengan antrean alert mendesak yang harus dianalisis |
| **Alat Keamanan** | Anda bekerja hanya dengan beberapa alat, tetapi harus benar-benar menguasainya | Anda harus bekerja dengan enam puluh alat dan platform keamanan yang beragam |
| **Pengalaman Insiden** | Anda hanya melihat dan belajar dari dua serangan siber besar tahun lalu | Setiap minggu Anda menghadapi serangan dan pelanggaran keamanan, serta bisa belajar darinya |

## Langkah Selanjutnya
Langkah paling alami setelah L1 adalah menjadi analis SOC L2, tetapi Anda bebas memilih jalur lain! Saat menangani alert SIEM, Anda mungkin menyadari bahwa pekerjaan engineering lebih menarik bagi Anda. Selama serangan siber, Anda mungkin terpukau oleh tindakan CIRT. Anda juga mungkin merasa cocok menjadi manajer dan membangun jalur menuju peran CISO. Apa pun pilihannya, satu atau dua tahun pertama Anda adalah untuk mendapatkan pengalaman kerja nyata, dan agar waktu tersebut digunakan secara efektif, ikuti tips di bawah ini!

![sumber thm](https://tryhackme-images.s3.amazonaws.com/user-uploads/678ecc92c80aa206339f0f23/room-content/678ecc92c80aa206339f0f23-1757446133693.svg)

Answer the questions below

**How would you call a cyber security company providing SOC services?**
```
MSSP
```
**Which role naturally continues your SOC L1 analyst journey?**
```
SOC L2 Analyst
```
# Tantangan Akhir

Untuk tugas ini, bayangkan diri Anda sebagai seorang CISO di TrySecureMe, sebuah perusahaan multinasional besar. Anda mengawasi banyak departemen dan menangani insiden setiap bulan. Kali ini, sebanyak tujuh insiden terjadi secara bersamaan, dan Anda harus memilih orang yang tepat untuk menangani masing-masing insiden tersebut. Apakah Anda cukup memahami peran keamanan untuk menyelesaikan tantangan ini?

**Instruksi Situs Web**  
**Klik Tombol Hijau**

Buka situs web terlampir dengan mengklik tombol View Site di atas dan pertimbangkan untuk mengubah ukuran atau membukanya dalam layar penuh agar tampilannya lebih baik. Kemudian, seret dan lepaskan peran dari sisi kiri ke insiden di sisi kanan. Jika pilihan Anda benar, klaim flag Anda dan selesaikan tugasnya! Anda dapat mereset situs web kapan saja dengan mengklik tombol Reset.

![sumber thm](https://tryhackme-images.s3.amazonaws.com/user-uploads/678ecc92c80aa206339f0f23/room-content/678ecc92c80aa206339f0f23-1762383466452.png)

ini adalah role yg benar untuk menangani permasalahan di dalam case ini:
![](https://miro.medium.com/v2/resize:fit:720/format:webp/1*vgX_yUx_yNz9Y4cAsx4W0A.png)

Berikut penjelasan setiap role pada gambar TrySecureMe, dibuat sederhana dan mudah dipahami.

# Gambaran Besar Alur Tim Cyber Security

Bayangkan perusahaan punya “tim penjaga keamanan digital”.
Setiap orang punya tugas berbeda:

* Ada yang memantau alarm
* Ada yang memperbaiki sistem
* Ada yang memburu hacker
* Ada yang audit aturan keamanan
* Ada yang memimpin saat serangan terjadi

Karena itu, setiap kasus harus ditangani oleh role yang tepat.

# 1. CERT Lead — Robert

Robert

## Tugas Utama

Pemimpin tim tanggap insiden keamanan.

CERT = Computer Emergency Response Team.

## Apa yang dilakukan?

* Mengatur respon saat terjadi serangan besar
* Menentukan prioritas
* Koordinasi antar tim
* Mengambil keputusan cepat

## Contoh Kasus

> “Kantor di Prancis terkena ransomware. Respon cepat dibutuhkan!”

Ini cocok untuk CERT Lead karena:

* Serangan ransomware adalah insiden besar
* Butuh koordinasi cepat
* Banyak tim harus diarahkan sekaligus

## Analogi Mudah

Seperti komandan pemadam kebakaran saat gedung terbakar.

# 2. SOC L1 Analyst — Lucas

Lucas

## Tugas Utama

“Penjaga monitor” keamanan level pertama.

SOC = Security Operations Center.

## Apa yang dilakukan?

* Memantau alert dari SIEM
* Mengecek alarm awal
* Menentukan apakah ancaman asli atau false positive
* Eskalasi jika serius

## Contoh Kasus

> “SIEM membuat alert brute-force di firewall.”

Ini cocok untuk SOC L1 karena:

* Mereka yang pertama menerima alert
* Tugas mereka melakukan triage awal

## Apa itu Triage?

Memilah:

* Bahaya atau tidak
* Prioritas tinggi atau rendah
* Perlu diteruskan atau tidak

## Analogi Mudah

Seperti petugas call center 112 yang menerima laporan pertama.


# 3. SOC L2 Analyst — Susan

Susan

## Tugas Utama

Analisis insiden lebih dalam.

## Apa yang dilakukan?

* Investigasi malware
* Analisis log detail
* Threat hunting
* Menentukan dampak serangan

## Contoh Kasus

> “HR manager membuka phishing malware. Siapa yang melakukan analisis mendalam?”

Jawaban: SOC L2 Analyst.

Karena:

* Malware perlu investigasi teknis
* Harus dicek penyebarannya
* Harus dianalisis bagaimana malware bekerja

## Analogi Mudah

Kalau L1 itu dokter umum, maka L2 adalah dokter spesialis.


# 4. GRC Auditor — Nick

Nick

## Tugas Utama

Mengurus aturan, compliance, dan audit.

GRC = Governance, Risk, Compliance.

## Apa yang dilakukan?

* Audit keamanan
* Memastikan perusahaan patuh standar
* Mengecek risiko bisnis
* Membuat kebijakan keamanan

## Contoh Kasus

> “Server kartu kredit membutuhkan audit PCI DSS.”

Jawaban: GRC Auditor.

Karena:

* PCI DSS adalah standar compliance
* Audit dan kepatuhan adalah tugas GRC

## Apa itu PCI DSS?

Standar keamanan untuk data kartu kredit.

## Analogi Mudah

Seperti auditor keuangan, tapi untuk keamanan IT.


# 5. Penetration Tester — Ben

Ben

## Tugas Utama

Mencari celah keamanan sebelum hacker menemukannya.

## Apa yang dilakukan?

* Simulasi hacking legal
* Vulnerability assessment
* Uji keamanan aplikasi/server
* Exploit testing

## Contoh Kasus

> “Cek versi baru hyrackme.thm untuk vulnerability.”

Jawaban: Penetration Tester.

Karena:

* Tujuannya mencari kelemahan sistem
* Butuh pengujian seperti hacker

## Analogi Mudah

Seperti “tester keamanan gedung” yang mencoba membobol pintu untuk mencari kelemahan.


# 6. SOC Engineer — Eugen

Eugen

## Tugas Utama

Membangun dan memperbaiki sistem SOC.

## Apa yang dilakukan?

* Mengelola SIEM
* Membuat rule detection
* Troubleshooting tools security
* Integrasi log dan monitoring

## Contoh Kasus

> “SIEM tidak tersedia karena storage penuh.”

Jawaban: SOC Engineer.

Karena:

* Ini masalah infrastruktur/security tools
* Bukan investigasi serangan

## Analogi Mudah

Seperti teknisi mesin yang memastikan CCTV dan alarm tetap bekerja.


# 7. Threat Researcher — Alice

Alice

## Tugas Utama

Mempelajari hacker dan teknik serangan terbaru.

## Apa yang dilakukan?

* Riset kelompok hacker
* Analisis TTP (Tactics, Techniques, Procedures)
* Membuat threat intelligence
* Mempelajari malware baru

## Contoh Kasus

> “FIN7 sedang menarget perusahaan kita. Siapa yang menganalisis taktik mereka?”

Jawaban: Threat Researcher.

Karena:

* FIN7 adalah kelompok threat actor
* Perlu riset pola dan strategi mereka

# Ringkasan Cepat

| Role               | Fokus Utama             | Contoh Kerja          |
| ------------------ | ----------------------- | --------------------- |
| CERT Lead          | Memimpin respon insiden | Koordinasi ransomware |
| SOC L1             | Monitor alert awal      | Cek alert SIEM        |
| SOC L2             | Investigasi mendalam    | Analisis malware      |
| GRC Auditor        | Audit & compliance      | PCI DSS               |
| Penetration Tester | Cari celah keamanan     | Uji vulnerability     |
| SOC Engineer       | Perbaiki tools SOC      | SIEM error            |
| Threat Researcher  | Riset hacker            | Analisis FIN7         |



Answer the questions below


**What flag did you claim after completing the final challenge?**
```
THM{trysecureme_is_secured!}
```