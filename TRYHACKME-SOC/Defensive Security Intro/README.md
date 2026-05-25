# Pengantar Keamanan Defensif
Pada pelajaran sebelumnya, kita mempelajari tentang keamanan ofensif, yang bertujuan untuk mengidentifikasi dan mengeksploitasi kerentanan sistem guna meningkatkan langkah-langkah keamanan. Ini mencakup eksploitasi bug perangkat lunak, memanfaatkan konfigurasi yang tidak aman, dan mengambil keuntungan dari kebijakan kontrol akses yang tidak diterapkan, di antara strategi lainnya. Tim merah (red team) dan penguji penetrasi (penetration tester) mengkhususkan diri dalam teknik-teknik ofensif ini.

Dalam pelajaran ini, kita akan membahas pasangannya, yaitu keamanan defensif. Keamanan defensif berfokus pada dua tugas utama:

1. Mencegah terjadinya intrusi
2. Mendeteksi intrusi saat terjadi dan meresponsnya dengan tepat

Tim biru (blue team) merupakan bagian dari lanskap keamanan defensif.

Beberapa tugas yang berkaitan dengan keamanan defensif meliputi:

- Kesadaran keamanan siber pengguna: Melatih pengguna tentang keamanan siber membantu melindungi dari serangan yang menargetkan sistem mereka.
- Mendokumentasikan dan mengelola aset: Kita perlu mengetahui sistem dan perangkat yang harus kita kelola dan lindungi dengan baik.
- Memperbarui dan menambal sistem: Memastikan bahwa komputer, server, dan perangkat jaringan diperbarui dan ditambal dengan benar terhadap setiap kerentanan (kelemahan) yang diketahui.
- Menyiapkan perangkat keamanan pencegahan: firewall dan intrusion prevention system (IPS) merupakan komponen penting dari keamanan pencegahan. Firewall mengontrol lalu lintas jaringan apa yang dapat masuk dan keluar dari sistem atau jaringan. IPS memblokir lalu lintas jaringan apa pun yang sesuai dengan aturan dan tanda tangan serangan yang ada.
- Menyiapkan perangkat pencatatan dan pemantauan: Pencatatan dan pemantauan jaringan yang tepat sangat penting untuk mendeteksi aktivitas berbahaya dan intrusi. Jika perangkat baru yang tidak sah muncul di jaringan kita, kita harus dapat mendeteksinya.

Masih banyak hal lain dalam keamanan defensif. Selain hal-hal di atas, kita juga akan membahas topik terkait berikut:

- Security Operations Center (SOC)
- Threat Intelligence
- Digital Forensics and Incident Response (DFIR)
- Analisis Malware

## Answer the questions below
**Which team focuses on defensive security?**
```
Blue Team
```

# Areas of Defensive Security

In this task, we will cover two main topics related to defensive security:

- Security Operations Center (SOC), where we cover Threat Intelligence
- Digital Forensics and Incident Response (DFIR), where we also cover Malware Analysis

## Security Operations Center (SOC)

A Security Operations Center (SOC) is a team of cyber security professionals that monitors the network and its systems to detect malicious cyber security events. Some of the main areas of interest for a SOC are:

- **Vulnerabilities**: Whenever a system vulnerability (weakness) is discovered, it is essential to fix it by installing a proper update or patch. When a fix is unavailable, the necessary measures should be taken to prevent an attacker from exploiting it. Although remediating vulnerabilities is vital to a SOC, it is not necessarily assigned to them.
- **Policy violations**: A security policy is a set of rules required to protect the network and systems. For example, it might be a policy violation if users upload confidential company data to an online storage service.
- **Unauthorized activity**: Consider the case where a user’s login name and password are stolen, and the attacker uses them to log into the network. A SOC must detect and block such an event as soon as possible before further damage is done.
- **Network intrusions**: No matter how good your security is, there is always a chance for an intrusion. An intrusion can occur when a user clicks on a malicious link or when an attacker exploits a public server. Either way, when an intrusion occurs, we must detect it as soon as possible to prevent further damage.

Security operations cover various tasks to ensure protection; one such task is threat intelligence.

![](https://tryhackme-images.s3.amazonaws.com/user-uploads/5f04259cf9bf5b57aed2c476/room-content/b5ac9a7b366ec258f9491899a9840f44.png)

## Threat Intelligence

In this context, intelligence refers to information you gather about actual and potential enemies. A threat is any action that can disrupt or adversely affect a system. Threat intelligence collects information to help the company better prepare against potential adversaries. The purpose would be to achieve a threat-informed defence. Different companies have different adversaries. Some adversaries might seek to steal customer data from a mobile operator; however, other adversaries are interested in halting the production in a petroleum refinery. Example adversaries include a nation-state cyber army working for political reasons and a ransomware group acting for financial purposes. Based on the company (target), we can expect adversaries.

![](https://tryhackme-images.s3.amazonaws.com/user-uploads/5f04259cf9bf5b57aed2c476/room-content/ad86b4613e8c0f852ae88be79d5f056f.png)

Intelligence needs data. Data has to be collected, processed, and analyzed. Data is collected from local sources such as network logs and public sources such as forums. Data processing arranges it into a format suitable for analysis. The analysis phase seeks to find more information about the attackers and their motives; moreover, it aims to create a list of recommendations and actionable steps.

Learning about your adversaries lets you know their tactics, techniques, and procedures. As a result of threat intelligence, we identify the threat actor (adversary) and predict their activity. Consequently, we can mitigate their attacks and prepare a response strategy.

## Digital Forensics and Incident Response (DFIR)

This section is about Digital Forensics and Incident Response (DFIR), and we will cover:

- Digital Forensics
- Incident Response
- Malware Analysis

## Digital Forensics

Forensics is the application of science to investigate crimes and establish facts. With the use and spread of digital systems, such as computers and smartphones, a new branch of forensics was born to investigate related crimes: computer forensics, which later evolved into digital forensics.

In defensive security, the focus of digital forensics shifts to analyzing evidence of an attack and its perpetrators and other areas such as intellectual property theft, cyber espionage, and possession of unauthorized content. Consequently, digital forensics will focus on different areas, such as:

- **File System**: Analyzing a digital forensics image (low-level copy) of a system’s storage reveals much information, such as installed programs, created files, partially overwritten files, and deleted files.
- **System memory**: If the attacker runs their malicious program in memory without saving it to the disk, taking a forensic image (low-level copy) of the system memory is the best way to analyze its contents and learn about the attack.
- **System logs**: Each client and server computer maintains different log files about what is happening. Log files provide plenty of information about what happened on a system. Even if the attacker tries to clear their traces, some traces will remain.
- **Network logs**: Logs of the network packets that have traversed a network would help answer more questions about whether an attack is occurring and what it entails.