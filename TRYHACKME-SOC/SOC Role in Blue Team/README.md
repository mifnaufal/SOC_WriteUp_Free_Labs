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

# Advancing SOC Career
## SOC Path
Starting as a SOC L1 analyst may be a great option to broaden your cyber world awareness and better understand the more specialized roles. Moreover, even the entry-level SOC L1 role can be fun and engaging: You will deal with real attacks, protect the company from advanced threat groups, and learn a lot during the process. Let's see how you can start:

1. Gain core SOC skills and practice them. Related skills like red teaming or general IT would help, too!
2. Be proactive, try yourself in CTFs, stay in the loop of cyber news, and consider the SAL1 certification!
3. Prepare for an interview, learn the difference between an internal SOC and MSSP, and apply for a job!
4. After working for some time in a junior position, consider preparing and advancing to more senior roles!

## Internal SOC vs MSSP

Not every organization has the expertise to operate a SOC on its own and relies on a Managed Security Services Provider (MSSP), a company that delivers outsourced security services, most commonly SOC, to its clients. Working at MSSP is typically high-pressure, but it is also a good option to quickstart your career. While we recommend applying for any open SOC position as your first job, it's also important to understand the differences:

