# Kumpulan Tugas Konsep Jaringan


## Tugas Bab 1

1. Jelaskan pengertian jaringan komputer dengan menyebutkan empat unsur 
pokoknya. 
Jaringan komputer adalah sekumpulan perangkat otonom yang saling terhubung 
melalui media komunikasi untuk bertukar data dan berbagi sumber daya 
berdasarkan protokol disepakati, dengan empat unsur berupa perangkat akhir, 
media komunikasi, perangkat perantara, dan protokol. 
2. Apa yang dimaksud dengan perangkat otonom dalam definisi jaringan? 
Perangkat otonom berarti setiap perangkat tetap memiliki fungsi, kendali 
komputasi, identitas, serta sumber daya tersendiri yang tidak hilang saat 
bergabung ke jaringan. 
3. Bedakan data, sinyal, dan paket. 
Data adalah representasi informasi, sinyal adalah bentuk fisik pembawa data 
pada media, sedangkan paket adalah unit-unit kecil hasil pembagian data yang 
dilengkapi informasi kendali untuk dikirim melalui jaringan. 
4. Jelaskan perbedaan PAN, LAN, MAN, dan WAN tanpa hanya menggunakan 
ukuran jarak. 
Klasifikasi keempatnya dibedakan berdasarkan wilayah layanan, teknologi, 
kepemilikan, dan pola operasi; PAN mencakup area personal, LAN melayani 
area lokal terbatas, MAN menghubungkan kawasan metropolitan, sedangkan 
WAN mencakup jaringan antarwilayah luas yang melibatkan operator. 
5. Apa perbedaan intranet, ekstranet, dan Internet publik? 
Perbedaannya terletak pada batasan akses. Intranet khusus untuk internal 
organisasi, Ekstranet memperluas sebagian akses internal ke pihak luar tertentu, 
dan Internet publik merupakan akses terbuka bagi masyarakat luas. 
6. Mengapa Wi-Fi tidak dapat disamakan dengan Internet? 
Wi-Fi hanya teknologi media nirkabel untuk menyediakan akses jaringan lokal, 
sehingga perangkat dapat terhubung ke Wi-Fi tanpa harus memiliki jalur menuju 
Internet publik. 
7. Jelaskan perbedaan client, server, dan peer. 
Client adalah pihak yang meminta layanan, server adalah penyedia layanan 
terpusat untuk banyak client, sedangkan peer adalah node yang bertindak 
sebagai peminta sekaligus penyedia sumber daya secara bersamaan. 
8. Apa perbedaan bandwidth, throughput, dan goodput? 
Bandwidth adalah kapasitas nominal maksimum jalur, throughput adalah laju 
aktual data yang dipindahkan termasuk overhead, sedangkan goodput adalah 
laju data aplikasi murni yang berhasil diterima. 
9. Sebutkan empat komponen nodal delay. 
Komponen penentu delay pada node terdiri atas processing delay, queuing 
delay, transmission delay, dan propagation delay. 
10. Mengapa Web tidak sama dengan Internet? 
Internet adalah seluruh infrastruktur jaringan global, sedangkan Web merupakan 
salah satu layanan aplikasi yang berjalan di atas infrastruktur Internet. 
11. Sebuah paket berukuran 1.000 byte dikirim melalui tautan 10 Mbps. Hitung 
transmission delay ideal paket tersebut. Jelaskan komponen delay yang belum 
tercakup. 
Nilai transmission delay ideal paket 1.000 byte pada jalur 10 Mbps adalah 0,8 
milidetik. Perhitungan ini belum mencakup processing delay, queuing delay 
dalam antrean, serta propagation delay di media. 
12. Sebuah kampus memiliki koneksi Internet 2 Gbps, tetapi pengguna di satu lantai 
hanya memperoleh throughput rendah. Susun sedikitnya lima hipotesis yang 
tidak langsung menyalahkan koneksi ISP. 
Masalah throughput lokal bisa disebabkan interferensi sinyal Wi-Fi, 
penumpukan pengguna pada access point, masalah port atau switch lokal, 
pembatasan kebijakan jaringan internal, atau keterbatasan kinerja perangkat 
pengguna. 
13. Bandingkan kebutuhan jaringan untuk transfer berkas cadangan dan panggilan 
video. Metrik apa yang paling penting bagi masing-masing aplikasi? 
transfer berkas cadangan mengutamakan throughput tinggi serta keutuhan data, 
sedangkan panggilan video lebih membutuhkan delay rendah, variasi delay 
minim, serta toleransi terhadap sedikit paket hilang. 
14. Sebuah organisasi mempunyai dua koneksi Internet dari dua operator. Keduanya 
melewati tiang dan jalur ducting yang sama. Evaluasi kualitas redundansinya. 
Redundansi tersebut buruk karena meskipun menggunakan dua operator 
berbeda, keduanya masih melewati tiang dan jalur fisik yang sama sehingga 
rentan terputus bersamaan saat terjadi kerusakan fisik. 
15. Jelaskan mengapa penambahan bandwidth tidak selalu mengurangi waktu 
akses ke server yang sangat jauh. 
Menambah bandwidth tidak mengurangi waktu akses ke server jauh karena 
batas waktu tempuh data dominan dipengaruhi oleh jarak fisik dan kecepatan 
rambat sinyal. 
16. Sebuah layanan tersedia 99,9% selama satu tahun. Hitung perkiraan maksimum 
durasi ketidaktersediaannya. Bandingkan dengan target 99,99%. 
layanan dengan availability 99,9% mengizinkan waktu mati maksimum sekitar 8 
jam 46 menit per tahun, sedangkan availability 99,99% menekan batas waktu 
mati hingga sekitar 52 menit per tahun. 
17. Analisis kelebihan dan kelemahan client–server serta P2P untuk distribusi 
berkas berukuran besar kepada ribuan pengguna. 
Client-server memudahkan kontrol terpusat tetapi rawan menjadi penghambat 
saat diakses masif, sedangkan P2P sangat mudah dikembangkan kapasitasnya 
namun sulit dalam pengelolaan keamanan dan kepastian ketersediaan data. 
18. Berikan contoh ketika topologi fisik dan topologi logis pada jaringan kampus 
berbeda. 
aringan kampus dapat berbentuk bintang secara fisik karena seluruh kabel 
menuju switch terpusat, tetapi memiliki topologi logis berbeda akibat penerapan 
beberapa VLAN dan jalur routing terpisah. 
19. Rancang klasifikasi kebutuhan jaringan kampus untuk mahasiswa, staf 
administrasi, tamu, kamera pengawas, dan laboratorium riset. Jelaskan alasan 
segmentasi dan aturan komunikasi utamanya. 
Kampus perlu memisahkan jaringan Mahasiswa, Staf Administrasi, Tamu, 
Kamera Pengawas, dan Laboratorium Riset ke dalam subnet terpisah. 
Pembatasan lalu lintas menggunakan aturan firewall diterapkan agar akses data 
sensitif tetap terlindungi. 
20. Evaluasi pernyataan: “Jaringan internal tidak memerlukan enkripsi karena sudah 
dilindungi firewall.” Gunakan prinsip kerahasiaan, integritas, dan ketersediaan. 
Anggapan jaringan internal pasti aman adalah keliru karena ancaman dapat 
berasal dari perangkat internal terinfeksi atau kebocoran akses. Tanpa enkripsi, 
data internal tetap rentan disadap atau diubah. 
21. Diskusikan mengapa Internet dapat berkembang tanpa otoritas teknis pusat 
tunggal. Jelaskan manfaat serta risikonya. 
Internet tumbuh pesat berkat konsensus terbuka organisasi seperti IETF dan 
ICANN tanpa ketergantungan pada satu pihak. Namun, model ini membawa 
risiko sulitnya koordinasi global dan potensi dampak luas akibat kesalahan rute 
22. Bandingkan circuit switching dan packet switching untuk layanan suara. 
Jelaskan mengapa suara modern tetap dapat berjalan pada jaringan paket. 
Circuit switching menjamin kapasitas tetapi membuang sumber daya saat diam, 
sedangkan packet switching membagi kapasitas secara dinamis. Suara modern 
dapat berjalan lancar di atas packet switching berkat penerapan prioritas lalu 
lintas. 
23. Ambil satu keluhan nyata atau hipotetis berupa “Internet lambat”. Susun 
prosedur pengumpulan bukti, pengujian hipotesis, dan kriteria keberhasilan 
perbaikannya. 
Diagnosa dimulai dengan mengumpulkan metrik kinerja, dilanjutkan pengujian 
bertahap dari jaringan lokal hingga ke server tujuan, lalu diakhiri dengan 
perbaikan titik hambatan sesuai indikator acuan. 
24. Kunjungi statistik IPv6 Google atau sumber pengukuran APNIC. Catat tanggal, 
definisi metrik, populasi yang diukur, dan nilai untuk Indonesia. Jelaskan 
mengapa angka dari dua sumber dapat berbeda. 
Perbedaan angka statistik dari Google dan APNIC terjadi karena beda 
metodologi; Google mengukur pengguna yang mengakses layanannya secara 
langsung, sedangkan APNIC menguji kapabilitas pengguna melalui eksperimen 
iklan. 
25. Buat argumen mengenai penggunaan satelit orbit rendah sebagai koneksi utama 
atau cadangan bagi kampus di wilayah terpencil. Nilai kinerja, biaya, 
ketergantungan cuaca, pengelolaan, dan keamanan. 
Satelit orbit rendah sangat berguna sebagai jalur utama atau cadangan di 
wilayah terpencil karena latensinya jauh lebih rendah daripada satelit 
geostasioner. Namun, operasionalnya rentan terpengaruh cuaca dan 
membutuhkan biaya relatif tinggi. 
26. Jelaskan bagaimana otomatisasi jaringan dapat meningkatkan konsistensi 
sekaligus memperbesar dampak kesalahan. Usulkan kontrol teknis dan proses 
untuk mengurangi risiko tersebut. 
Otomatisasi mempercepat konsistensi konfigurasi tetapi berisiko menyebarkan 
kesalahan ke seluruh jaringan secara instan. Risiko ini dimitigasi melalui 
pengujian bertahap, validasi otomatis, serta mekanisme pembatalan 
perubahan. 
27. Tentang kabel UTP 
Kabel UTP dikategorikan berdasarkan kapasitas dan frekuensinya, dimulai dari 
Cat 1 yang khusus untuk komunikasi suara telepon analog , Cat 2–4 untuk 
teknologi jaringan lama seperti Token Ring, Cat 5/5e yang mendukung kecepatan 
hingga 1 Gbps, Cat 6/6a untuk jaringan 10 Gbps dengan perlindungan crosstalk 
lebih baik, Cat 7/7a (10 Gbps dengan shielding ketat hingga 600–1000 MHz), 
hingga Cat 8 yang mendukung kecepatan 25–40 Gbps khusus untuk kebutuhan 
data center jarak pendek. 
28. Standar Wi-Fi abgn 
Standar Wi-Fi dikembangkan oleh IEEE melalui seri 802.11, dimulai dari 802.11b 
(Wi-Fi 1) yang berjalan di pita 2,4 GHz dengan kecepatan maksimal 11 Mbps, 
802.11a (Wi-Fi 2) di pita 5 GHz dengan kecepatan hingga 54 Mbps, 802.11g (Wi-Fi 3) yang menggabungkan pita 2,4 GHz dengan kecepatan 54 Mbps, serta 802.11n 
(Wi-Fi 4) yang mendukung pita ganda 2,4 GHz dan 5 GHz dengan kecepatan 
hingga 600 Mbps memanfaatkan teknologi Multi-Input Multi-Output (MIMO). 

## Tugas Bab 2

1. **Jelaskan alasan komunikasi jaringan disusun berlapis.**
Komunikasi jaringan disusun berlapis untuk menerapkan prinsip abstraksi dan modularitas, sehingga kompleksitas sistem terurai menjadi bagian-bagian yang lebih kecil, independen, dan mudah dikelola tanpa mengharuskan suatu lapisan mengetahui detail mekanisme internal lapisan lainnya.

2. **Bedakan layanan, antarmuka, dan protokol.**
Layanan merupakan serangkaian kemampuan atau fungsi abstrak yang disediakan oleh suatu lapisan ke lapisan tepat di atasnya; antarmuka adalah sarana operasional formal bagi lapisan atas untuk mengakses layanan tersebut; sedangkan protokol adalah aturan dan format baku pertukaran pesan yang disepakati antarentitas pada lapisan yang sama (*peer entities*).

3. **Sebutkan tujuh lapisan OSI dari bawah ke atas beserta fungsi utamanya.**
Tujuh lapisan model OSI dari bawah ke atas meliputi Lapisan Fisik (transmisi bit mentah melalui media fisik), Datalink (pengiriman frame bebas galat antar-node bertetangga), Jaringan (perutean dan pengalamatan logis paket end-to-end), Transpor (keandalan dan kontrol aliran segmen antarproses), Sesi (pengelolaan dan sinkronisasi dialog komunikasi), Presentasi (penafsiran sintaksis, translasi format data, dan enkripsi), serta Aplikasi (penyediaan antarmuka bagi aplikasi pengguna akhir untuk mengakses layanan jaringan).

4. **Sebutkan empat lapisan model TCP/IP.**
Empat lapisan pada arsitektur model TCP/IP standar meliputi Lapisan Akses Jaringan (*Network Access Layer*), Lapisan Internet (*Internet Layer*), Lapisan Transpor (*Transport Layer*), dan Lapisan Aplikasi (*Application Layer*).

5. **Mengapa model TCP/IP kadang disajikan sebagai lima lapisan?**
Model TCP/IP kerap disajikan sebagai model lima lapisan untuk kepentingan pedagogis dengan memecah *Network Access Layer* menjadi *Data Link Layer* dan *Physical Layer*, sehingga pengajar dan pembelajar dapat menganalisis perbedaan mendasar antara representasi sinyal transmisi fisik dan protokol pembingkaian frame lokal secara lebih terstruktur menyerupai OSI.

6. **Apa perbedaan frame, IP packet, TCP segment, dan UDP datagram?**
Frame adalah unit data protokol (PDU) pada lapisan datalink yang dilengkapi alamat fisik; paket IP adalah PDU lapisan jaringan yang memuat alamat logis global sumber serta tujuan; segmen TCP adalah PDU lapisan transpor berorientasi koneksi yang mengusung nomor urut dan mekanisme kendali; sedangkan datagram UDP adalah PDU transpor nir-koneksi berbobot ringan tanpa jaminan keandalan pengiriman.

7. **Definisikan header, trailer, dan payload.**
Header adalah informasi kendali protokol yang ditambahkan di awal unit data; trailer adalah data kendali tambahan (seperti kode verifikasi galat FCS) yang diletakkan di akhir unit data; sedangkan payload adalah data inti atau substansi pesan bawaan dari lapisan di atasnya yang hendak dihantarkan.

8. **Jelaskan enkapsulasi dan dekapsulasi.**
Enkapsulasi adalah mekanisme pembungkusan payload oleh protokol lapisan tertentu dengan menambahkan header dan trailer yang sesuai saat data bergerak turun ke media fisik; sementara dekapsulasi adalah proses pelepasan header dan trailer tersebut secara bertahap saat data bergerak naik di sisi penerima hingga menyisakan data aplikasi asli.

9. **Apa fungsi multiplexing dan demultiplexing?**
Multiplexing berfungsi menggabungkan berbagai aliran data dari banyak aplikasi atau protokol lapisan atas ke dalam satu kanal atau protokol lapisan bawah yang sama, sedangkan demultiplexing berfungsi memilah dan mengarahkan kembali data yang tiba ke soket atau entitas aplikasi lapisan atas yang berhak menerimanya.

10. **Mengapa OSI tidak boleh dianggap sebagai spesifikasi implementasi?**
Model OSI dirancang murni sebagai kerangka referensi teoretis (*reference model*) konseptual yang mendefinisikan apa yang harus dilakukan oleh tiap lapisan, bukan bagaimana hal tersebut diimplementasikan secara komputasional melalui struktur data riil, panggilan kernel, maupun efisiensi tumpukan perangkat lunak dunia nyata.


11. **Petakan HTTP, TLS, TCP, UDP, QUIC, IPv6, ICMP, Ethernet, Wi-Fi, dan DNS ke model TCP/IP. Tandai protokol yang pemetaannya memerlukan penjelasan.**
Ethernet dan Wi-Fi menempati Lapisan Akses Jaringan; IPv6 dan ICMP berada pada Lapisan Internet; TCP dan UDP berada pada Lapisan Transpor; sedangkan HTTP dan DNS berada pada Lapisan Aplikasi. Protokol yang membutuhkan penjelasan khusus mencakup ICMP (beroperasi di Lapisan Internet meski dienkapsulasi paket IP), TLS (kerap berada di antara Transpor dan Aplikasi), serta QUIC (berjalan di atas UDP Lapisan Transpor namun mengintegrasikan TLS 1.3 dan logika transport mandiri di ruang pengguna untuk melayani HTTP/3).

12. **Gambarkan enkapsulasi permintaan DNS melalui UDP, IPv4, dan Ethernet. Sebutkan pengenal yang digunakan pada setiap batas.**
Enkapsulasi dimulai saat payload DNS ditempatkan di dalam UDP dengan menyertakan Nomor Port (port 53) sebagai pengenal batas transpor, kemudian dibungkus ke dalam paket IPv4 dengan kolom *Protocol Identifier* bernilai 17 sebagai pengenal batas internet, dan terakhir dibungkus ke dalam frame Ethernet dengan *EtherType* `0x0800` serta alamat MAC fisik sebelum dikirim ke media transmisi.

13. **Ulangi soal sebelumnya untuk HTTP/3 melalui QUIC. Jelaskan mengapa QUIC tetap dapat dianggap transport meskipun menggunakan UDP.**
Pada HTTP/3, data aplikasi dibungkus oleh QUIC yang telah menyatukan enkripsi bawaan dan kendali transmisi, kemudian seluruh entitas QUIC dienkapsulasi ke dalam UDP datagram bertanda port 443, di mana QUIC tetap sah diposisikan secara fungsional sebagai lapisan transpor karena mengambil alih seluruh tanggung jawab keandalan transmisi, penataan urutan data, kendali kongesti, dan penanganan koneksi independen dari UDP.

14. **Dua host berada pada subnet berbeda. Jelaskan header mana yang berubah dan tetap ketika paket melewati satu router, dengan mengabaikan NAT.**
Ketika paket melintasi router tanpa NAT, header lapisan jaringan (IPv4/IPv6) tetap mempertahankan alamat IP sumber dan tujuan asli (hanya nilai TTL/Hop Limit berkurang satu dan *checksum* header dihitung ulang), sedangkan header lapisan datalink (Ethernet) sepenuhnya berubah karena alamat MAC sumber digantikan oleh MAC interface keluar router dan MAC tujuan diubah menjadi MAC hop berikutnya.

15. **Jelaskan perubahan analisis apabila router tersebut juga melakukan NAT/PAT.**
Apabila router mengaktifkan fungsi NAT/PAT, alamat IP sumber pada header internet akan diubah menjadi alamat IP publik antarmuka router, nomor port sumber pada header lapisan transpor (TCP/UDP) dimodifikasi untuk membedakan sesi, dan *checksum* pada lapisan internet maupun transpor wajib dihitung ulang sebelum diteruskan ke tujuan luar.

16. **Sebuah capture menunjukkan checksum TCP salah pada paket keluar, tetapi tidak ada gangguan komunikasi. Ajukan hipotesis yang berkaitan dengan NIC offload.**
Kondisi di mana tangkapan paket lokal memperlihatkan nilai *checksum* TCP yang korup tanpa memicu gangguan komunikasi umumnya disebabkan oleh fitur *TCP Checksum Offloading* pada kartu jaringan (NIC), di mana *packet sniffer* menyadap paket pada lapisan kernel OS sebelum paket mencapai prosesor keras NIC yang sebenarnya bertugas menghitung dan menempelkan nilai *checksum* valid sebelum transmisi fisik.

17. **Pengguna dapat membuka portal dengan alamat IP, tetapi tidak dengan nama. Gunakan model lapisan untuk menyusun diagnosis.**
Ketidakmampuan mengakses portal melalui nama domain kendati akses via IP berhasil membuktikan bahwa tumpukan lapisan Fisik, Datalink, Internet (IP rute), dan Transpor beroperasi normal, sehingga letak kegagalan terisolasi secara presisi pada layanan resolusi nama domain (DNS) di Lapisan Aplikasi yang terganggu akibat konfigurasi server DNS klien yang salah, pemblokiran lalu lintas port 53, atau kegagalan *resolver*.

18. **Ping ke server berhasil, tetapi HTTPS gagal. Susun sedikitnya enam hipotesis pada lapisan Transport hingga Application.**
Kegagalan HTTPS kendati ICMP echo berhasil dapat dihipotesiskan melalui enam skenario berikut: penolakan jabat tangan TCP akibat port 443 tertutup di sisi server (*Transport*), pemblokiran port 443 oleh aturan *firewall* atau ACL di sepanjang jalur (*Transport*), kegagalan negosiasi algoritma cipher suite pada jabat tangan TLS (*Presentation/Security*), ketidakcocokan atau kedaluwarsanya sertifikat digital SSL/TLS (*Presentation/Security*), penolakan koneksi oleh konfigurasi *Virtual Host* web server (*Application*), atau kegagalan otentikasi proksi korporat yang memutus lalu lintas HTTPS (*Application*).

19. **Bandingkan sesi aplikasi dengan koneksi TCP. Berikan contoh ketika sesi bertahan setelah koneksi berubah.**
Koneksi TCP adalah asosiasi transpor berbasis status *stateful* sementara yang ditentukan oleh pertukaran paket kontrol SYN-ACK, sedangkan sesi aplikasi adalah hubungan dialog logis berjangka panjang antarpengguna; sebagai contoh, sesi otentikasi akun web browser tetap bertahan berjam-jam melalui penggunaan token atau *cookie*, kendati koneksi TCP di bawahnya berulang kali diputus dan disambung ulang saat pengguna berpindah jaringan seluler ke Wi-Fi.

20. **Jelaskan mengapa enkripsi tidak dapat selalu ditempatkan secara mutlak pada Presentation layer.**
Enkripsi tidak dapat selalu diisolasi secara mutlak pada Lapisan Presentasi karena kebutuhan keamanan modern menuntut perlindungan kontekstual di berbagai tingkatan arsitektur, seperti pengamanan link transmisi fisik pada L2 (MACsec), perlindungan jalur antar-router secara transparan pada L3 (IPsec), proteksi transpor end-to-end pada L4/L5 (TLS/QUIC), hingga enkripsi spesifik payload data di L7 (*Application Layer*) sebelum diserahkan ke tumpukan protokol jaringan.

21. **Evaluasi pernyataan: “Model OSI tidak lagi relevan karena Internet menggunakan TCP/IP.” Susun argumen akademik yang membedakan model, protokol, dan kegunaan pedagogis.**
Pernyataan tersebut kurang tepat karena model OSI tetap memiliki nilai pedagogis dan konseptual yang sangat tinggi sebagai taksonomi universal untuk mendiskusikan mekanisme jaringan, memetakan titik kegagalan, dan menyusun spesifikasi fungsional perangkat; kegagalan OSI di pasar terjadi pada tataran implementasi tumpukan protokolnya yang terlalu kaku dan birokratis dibanding kepraktisan pragmatis protokol TCP/IP, bukan pada hilangnya relevansi model teoretisnya.

22. **Analisis keuntungan dan kerugian *strict layering*. Kapan cross-layer information dapat membantu dan kapan ia merusak modularitas?**
Keuntungan *strict layering* terletak pada keterpisahan tanggung jawab yang rapi, kemudahan pemeliharaan, dan skalabilitas desain independen, sedangkan kerugiannya adalah inefisiensi komputasi serta hilangnya visibilitas konteks lingkungan; pemanfaatan informasi lintas lapisan (*cross-layer*) sangat menguntungkan pada kondisi saluran nirkabel dinamis (misalnya mengabarkan degradasi sinyal radio secara langsung ke modul kendali kongesti transpor), tetapi berisiko merusak modularitas bila menciptakan ketergantungan erat yang membuat tumpukan perangkat lunak rapuh terhadap pembaruan protokol di masa mendatang. 



## Soal 1 – Analisis Alamat IP

Diketahui beberapa alamat IP berikut:
1. `21.26.8.5`
2. `212.6.8.3`
3. `103.24.56.32`
4. `1.1.1.1`
5. `172.31.16.8`

**Tentukan untuk masing-masing IP:**
- IP Gateway
- Host Pertama
- Host Terakhir
- Broadcast
- IP Network

---

### Jawaban Soal 1:




| No | Alamat IP | Kelas & Mask | IP Network | Host Pertama | Host Terakhir | Broadcast | IP Gateway |
|:--:|:----------|:------------|:-----------|:-------------|:--------------|:----------|:-------------------------|
| 1 | `21.26.8.5` | Kelas A (`/8`) | `21.0.0.0` | `21.0.0.1` | `21.255.255.254` | `21.255.255.255` | `21.0.0.1` |
| 2 | `212.6.8.3` | Kelas C (`/24`) | `212.6.8.0` | `212.6.8.1` | `212.6.8.254` | `212.6.8.255` | `212.6.8.1` |
| 3 | `103.24.56.32` | Kelas A (`/8`) | `103.0.0.0` | `103.0.0.1` | `103.255.255.254` | `103.255.255.255` | `103.0.0.1` |
| 4 | `1.1.1.1` | Kelas A (`/8`) | `1.0.0.0` | `1.0.0.1` | `1.255.255.254` | `1.255.255.255` | `1.0.0.1` |
| 5 | `172.31.16.8` | Kelas B (`/16`) | `172.31.0.0` | `172.31.0.1` | `172.31.255.254` | `172.31.255.255` | `172.31.0.1` |

---

## Soal 2 – Visualisasi Sinyal Harmonisasi

Buatlah visualisasi sinyal harmonisasi dari deret **1, 3, 5, 7, 9,** menggunakan **Python**.

<details>
<summary><b>Klik untuk melihat kode</b></summary>

```python
import matplotlib.pyplot as plt
import numpy as np

f0 = 1.0  
fs = 1000  
durasi = 2.0  
t = np.linspace(0, durasi, int(fs * durasi), endpoint=False)

harmonik_list = [1, 3, 5, 7, 9]

fig, axes = plt.subplots(
    nrows=len(harmonik_list) + 1,
    ncols=1,
    figsize=(10, 10),
    sharex=True,
    sharey=True,
)

gelombang_superposisi = np.zeros_like(t)

for idx, n in enumerate(harmonik_list):
    amplitudo = 1.0 / n
    gelombang_n = amplitudo * np.sin(2 * np.pi * n * f0 * t)

    gelombang_superposisi += gelombang_n

    axes[idx].plot(
        t,
        gelombang_n,
        label=f"Harmonik ke-{n} (f = {n*f0:.1f} Hz, A = 1/{n})",
        color="royalblue",
        linewidth=1.2,
    )
    axes[idx].set_ylabel(f"H-{n}", fontsize=9)
    axes[idx].grid(True, linestyle="--", alpha=0.6)
    axes[idx].legend(loc="upper right", fontsize=8)

axes[-1].plot(
    t,
    gelombang_superposisi,
    label="Superposisi (Hasil Harmonisasi: Gelombang Kotak)",
    color="crimson",
    linewidth=1.8,
)
axes[-1].set_ylabel("Total", fontsize=9)
axes[-1].set_xlabel("Waktu (detik)", fontsize=10)
axes[-1].grid(True, linestyle="--", alpha=0.6)
axes[-1].legend(loc="upper right", fontsize=8)

plt.suptitle(
    "Visualisasi Harmonisasi Gelombang Sinus",
    fontsize=13,
    fontweight="bold",
)
plt.tight_layout()
plt.show()
```

</details>

---



## Soal 3 – Subnetting

Lakukan pembagian subnet (*subnetting*) untuk setiap jaringan berikut:

1. `192.168.1.0/24` dibagi menjadi **4 subnet**
2. `132.10.0.0/16` dibagi menjadi **10 subnet**
3. `17.8.0.0/16` dibagi menjadi **4 subnet**
4. `8.32.0.0/12` dibagi menjadi **6 subnet**

**Tentukan untuk setiap subnet:**
- IP Network
- Subnet Mask (prefix baru)
- Host Pertama
- Host Terakhir
- Broadcast
- Jumlah host per subnet

---

### Jawaban Soal 3:

---

### Bagian 1: `192.168.1.0/24` dibagi menjadi 4 Subnet

#### Langkah Perhitungan:
1. **Menentukan bit subnet yang dipinjam (s):**
   2^s >= 4 -> s = 2 bit (Prefix baru: 24 + 2 = /26)
2. **Ukuran blok subnet:**
   Interval Blok = 256 - 192 = 64 IP
3. **Jumlah host per subnet:**
   Jumlah Host Usable = 2^(32 - 26) - 2 = 2^6 - 2 = 64 - 2 = 62 host

#### Hasil Pembagian Subnet:

| Subnet | IP Network | Subnet Mask (Prefix) | Host Pertama | Host Terakhir | Broadcast | Jumlah Host Usable |
|:------:|:-----------|:---------------------|:-------------|:--------------|:----------|:------------------:|
| 1 | `192.168.1.0/26` | `255.255.255.192` (`/26`) | `192.168.1.1` | `192.168.1.62` | `192.168.1.63` | 62 |
| 2 | `192.168.1.64/26` | `255.255.255.192` (`/26`) | `192.168.1.65` | `192.168.1.126` | `192.168.1.127` | 62 |
| 3 | `192.168.1.128/26` | `255.255.255.192` (`/26`) | `192.168.1.129` | `192.168.1.190` | `192.168.1.191` | 62 |
| 4 | `192.168.1.192/26` | `255.255.255.192` (`/26`) | `192.168.1.193` | `192.168.1.254` | `192.168.1.255` | 62 |

---

### Bagian 2: `132.10.0.0/16` dibagi menjadi 10 Subnet

#### Langkah Perhitungan:
1. **Menentukan bit subnet yang dipinjam (s):**
   2^s >= 10 -> s = 4 bit (2^4 = 16 subnet tersedia, Prefix baru: 16 + 4 = /20)
2. **Ukuran blok subnet:**
   Interval Blok Oktet 3 = 256 - 240 = 16
   Setiap subnet mencakup 16 kelipatan pada oktet ketiga (total 16 x 256 = 4.096 IP).
3. **Jumlah host per subnet:**
   Jumlah Host Usable = 2^(32 - 20) - 2 = 2^12 - 2 = 4096 - 2 = 4.094 host

#### Hasil Pembagian 10 Subnet (dari 16 subnet yang tersedia):

| Subnet ke- | IP Network | Subnet Mask (Prefix) | Host Pertama | Host Terakhir | Broadcast | Jumlah Host Usable |
|:----------:|:-----------|:---------------------|:-------------|:--------------|:----------|:------------------:|
| 1 | `132.10.0.0/20` | `255.255.240.0` (`/20`) | `132.10.0.1` | `132.10.15.254` | `132.10.15.255` | 4094 |
| 2 | `132.10.16.0/20` | `255.255.240.0` (`/20`) | `132.10.16.1` | `132.10.31.254` | `132.10.31.255` | 4094 |
| 3 | `132.10.32.0/20` | `255.255.240.0` (`/20`) | `132.10.32.1` | `132.10.47.254` | `132.10.47.255` | 4094 |
| 4 | `132.10.48.0/20` | `255.255.240.0` (`/20`) | `132.10.48.1` | `132.10.63.254` | `132.10.63.255` | 4094 |
| 5 | `132.10.64.0/20` | `255.255.240.0` (`/20`) | `132.10.64.1` | `132.10.79.254` | `132.10.79.255` | 4094 |
| 6 | `132.10.80.0/20` | `255.255.240.0` (`/20`) | `132.10.80.1` | `132.10.95.254` | `132.10.95.255` | 4094 |
| 7 | `132.10.96.0/20` | `255.255.240.0` (`/20`) | `132.10.96.1` | `132.10.111.254` | `132.10.111.255` | 4094 |
| 8 | `132.10.112.0/20` | `255.255.240.0` (`/20`) | `132.10.112.1` | `132.10.127.254` | `132.10.127.255` | 4094 |
| 9 | `132.10.128.0/20` | `255.255.240.0` (`/20`) | `132.10.128.1` | `132.10.143.254` | `132.10.143.255` | 4094 |
| 10 | `132.10.144.0/20` | `255.255.240.0` (`/20`) | `132.10.144.1` | `132.10.159.254` | `132.10.159.255` | 4094 |

*(Subnet cadangan yang tersisa: Subnet 11 s/d 16, yaitu `132.10.160.0/20` hingga `132.10.240.0/20`)*

---

### Bagian 3: `17.8.0.0/16` dibagi menjadi 4 Subnet

#### Langkah Perhitungan:
1. **Menentukan bit subnet yang dipinjam (s):**
   2^s >= 4 -> s = 2 bit (Prefix baru: 16 + 2 = /18)
2. **Ukuran blok subnet:**
   Interval Blok Oktet 3 = 256 - 192 = 64
   Setiap subnet bertambah 64 pada oktet ketiga (total 64 x 256 = 16.384 IP).
3. **Jumlah host per subnet:**
   Jumlah Host Usable = 2^(32 - 18) - 2 = 2^14 - 2 = 16384 - 2 = 16.382 host

#### Hasil Pembagian Subnet:

| Subnet ke- | IP Network | Subnet Mask (Prefix) | Host Pertama | Host Terakhir | Broadcast | Jumlah Host Usable |
|:----------:|:-----------|:---------------------|:-------------|:--------------|:----------|:------------------:|
| 1 | `17.8.0.0/18` | `255.255.192.0` (`/18`) | `17.8.0.1` | `17.8.63.254` | `17.8.63.255` | 16382 |
| 2 | `17.8.64.0/18` | `255.255.192.0` (`/18`) | `17.8.64.1` | `17.8.127.254` | `17.8.127.255` | 16382 |
| 3 | `17.8.128.0/18` | `255.255.192.0` (`/18`) | `17.8.128.1` | `17.8.191.254` | `17.8.191.255` | 16382 |
| 4 | `17.8.192.0/18` | `255.255.192.0` (`/18`) | `17.8.192.1` | `17.8.255.254` | `17.8.255.255` | 16382 |

---

### Bagian 4: `8.32.0.0/12` dibagi menjadi 6 Subnet

#### Langkah Perhitungan:
1. **Analisis Blok Awal (`/12`):**
   - Subnet Mask awal: `255.240.0.0`
   - Rentang blok awal: `8.32.0.0` sampai `8.47.255.255` (ukuran blok = 16 pada oktet ke-2).
2. **Menentukan bit subnet yang dipinjam (s):**
   2^s >= 6 -> s = 3 bit (2^3 = 8 subnet tersedia)
3. **Ukuran blok subnet:**
   Interval Blok Oktet 2 = 256 - 254 = 2
   Setiap subnet bertambah sebesar 2 pada oktet ke-2 (total 2 x 256 x 256 = 131.072 IP).
4. **Jumlah host per subnet:**
   Jumlah Host Usable = 2^(32 - 15) - 2 = 2^17 - 2 = 131072 - 2 = 131.070 host

#### Hasil Pembagian 6 Subnet (dari 8 subnet yang tersedia):

| Subnet ke- | IP Network | Subnet Mask (Prefix) | Host Pertama | Host Terakhir | Broadcast | Jumlah Host Usable |
|:----------:|:-----------|:---------------------|:-------------|:--------------|:----------|:------------------:|
| 1 | `8.32.0.0/15` | `255.254.0.0` (`/15`) | `8.32.0.1` | `8.33.255.254` | `8.33.255.255` | 131070 |
| 2 | `8.34.0.0/15` | `255.254.0.0` (`/15`) | `8.34.0.1` | `8.35.255.254` | `8.35.255.255` | 131070 |
| 3 | `8.36.0.0/15` | `255.254.0.0` (`/15`) | `8.36.0.1` | `8.37.255.254` | `8.37.255.255` | 131070 |
| 4 | `8.38.0.0/15` | `255.254.0.0` (`/15`) | `8.38.0.1` | `8.39.255.254` | `8.39.255.255` | 131070 |
| 5 | `8.40.0.0/15` | `255.254.0.0` (`/15`) | `8.40.0.1` | `8.41.255.254` | `8.41.255.255` | 131070 |
| 6 | `8.42.0.0/15` | `255.254.0.0` (`/15`) | `8.42.0.1` | `8.43.255.254` | `8.43.255.255` | 131070 |

---

## Soal 4 – Analisis Traceroute & Mekanisme TTL

Lakukan analisis terhadap cara kerja **Traceroute** serta mekanisme **TTL (Time To Live)** pada jaringan komputer.

**Poin yang harus dibahas:**
- Pengertian dan fungsi **Traceroute**
- Pengertian dan fungsi **TTL (Time To Live)**
- Bagaimana **Traceroute** memanfaatkan **TTL** untuk memetakan jalur paket
- Peran **ICMP (Internet Control Message Protocol)** dalam proses Traceroute
- Contoh alur/langkah kerja Traceroute dari sumber ke tujuan

---

### Jawaban Soal 4:

#### 1. Pengertian dan Fungsi Traceroute
- **Pengertian:** Traceroute (pada sistem operasi Windows dinamai `tracert`, sedangkan pada Linux/macOS dinamai `traceroute`) adalah utilitas diagnostik jaringan berbasis CLI yang dirancang untuk melacak dan memetakan rute lompatan (*hop-by-hop route*) yang dilalui paket IP dari komputer pengirim (*source host*) ke komputer tujuan (*destination host*).
- **Fungsi Utama:**
  1. **Pemetaan Rute:** Menampilkan daftar alamat IP dan nama domain seluruh router perantara (*gateways / hops*) di sepanjang jalur transmisi data.
  2. **Pengukuran Latensi:** Mengukur waktu tempuh bolak-balik (*Round Trip Time* / RTT) paket ke setiap router, biasanya dilakukan sebanyak 3 kali per hop untuk melihat konsistensi latensi.
  3. **Troubleshooting Titik Hambatan:** Membantu mendeteksi titik terjadinya kemacetan (*bottleneck*), kehilangan paket (*packet loss*), *routing loop*, atau kegagalan koneksi (*network failure*).

#### 2. Pengertian dan Fungsi TTL (Time To Live)
- **Pengertian:** TTL adalah field berukuran 8-bit yang terletak pada header paket IPv4 (pada header IPv6 digantikan dengan istilah *Hop Limit*). Nilai TTL merupakan bilangan bulat antara 1 hingga 255.
- **Fungsi Utama TTL:**
  1. **Mencegah Infinite Routing Loop:** Jika terjadi kesalahan pada tabel routing router-router internet yang menyebabkan paket berputar bolak-balik (*looping*), paket tidak akan berputar selamanya yang dapat membebani kapasitas jaringan.
  2. **Mekanisme Dekrementasi:** Setiap kali sebuah router menerima dan meneruskan (*forward*) paket IP ke hop berikutnya, router wajib mengurangi nilai TTL sebesar 1:
     TTL_baru = TTL_lama - 1
  3. **Pembuangan Paket (*Packet Drop*):** Jika router menerima paket dengan nilai TTL = 1, saat dikurangi menjadi 0, router tidak boleh meneruskan paket tersebut. Router akan **membuang (*drop*)** paket tersebut dan mengirimkan laporan kesalahan ke pengirim asli.

#### 3. Bagaimana Traceroute Memanfaatkan TTL untuk Memetakan Jalur
Traceroute tidak dapat langsung meminta seluruh router perantara melaporkan diri sekaligus. Traceroute mengeksploitasi mekanisme penurunan TTL dengan teknik **Inkrementasi Bertahap (*TTL Incrementing*)**:
1. **Probe Hop 1:** Pengirim mengirim paket probe pertama dengan nilai TTL = 1. Ketika paket tiba di router pertama (hop 1), router mengurangi TTL menjadi 0, membuang paket, dan mengirimkan balasan kesalahan. Dari balasan ini, pengirim mengetahui IP router hop 1 dan latensinya.
2. **Probe Hop 2:** Pengirim mengirim paket probe kedua dengan nilai TTL = 2. Router 1 mengurangi TTL menjadi 1 lalu meneruskannya. Saat tiba di Router 2, TTL dikurangi menjadi 0, paket dibuang, dan Router 2 mengirimkan balasan. Pengirim mencatat IP router hop 2.
3. **Probe Seterusnya:** Proses diulang dengan menaikkan nilai TTL secara bertahap (TTL = 3, 4, 5, ..., n) hingga akhirnya paket mencapai host tujuan.

#### 4. Peran ICMP (Internet Control Message Protocol)
Protokol ICMP memegang peranan sangat vital sebagai media penyampai laporan dan umpan balik (*feedback*) bagi Traceroute:
1. **Laporan Time Exceeded (ICMP Type 11, Code 0):**  
   Setiap kali router perantara membuang paket akibat TTL habis (TTL = 0), router tersebut membangkitkan pesan **ICMP Type 11 Code 0 (Time-to-Live Exceeded in Transit)** dan mengirimkannya kembali ke pengirim probe. Header IP dari paket ICMP ini memuat alamat IP antarmuka router perantara tersebut, sehingga Traceroute dapat mencatat identitas hop tersebut.
2. **Penanda Akhir di Titik Tujuan (*Target Reached*):**
   - **Pada Windows (`tracert`):** Mengirim paket **ICMP Echo Request (Type 8)**. Saat paket mencapai server tujuan, server tujuan membalas dengan **ICMP Echo Reply (Type 0)**. Penerimaan balasan ini menandakan seluruh rute telah selesai dipetakan.
   - **Pada Linux/macOS (`traceroute`):** Mengirim probe datagram **UDP** ke nomor port tinggi yang tidak lazim (misalnya port 33434 hingga 33534). Ketika paket sampai di host tujuan, sistem tujuan menolak karena tidak ada aplikasi yang mendengarkan di port tersebut, lalu membalas dengan **ICMP Type 3 Code 3 (Destination Unreachable - Port Unreachable)**. Balasan ini memberitahukan utilitas traceroute bahwa tujuan akhir telah berhasil dicapai.

#### 5. Contoh Alur dan Langkah Kerja Traceroute

Misalkan sebuah PC Klien (`192.168.1.50`) menjalankan traceroute ke Web Server (`93.184.216.34`) dengan topologi sebagai berikut:

```
[PC Klien] ---> (Router 1) ---> (Router 2) ---> (Router 3) ---> [Web Server]
192.168.1.50    192.168.1.1     10.10.1.1       172.16.0.1      93.184.216.34
```

| Langkah | TTL Probe | Rute Perjalanan Paket | Tindakan di Router / Server | Paket Balasan yang Diterima Klien | Output Layar Traceroute |
|:-------:|:---------:|:----------------------|:----------------------------|:-----------------------------------|:------------------------|
| **1** | TTL = 1 | Klien -> Router 1 | Router 1 mengurangi TTL: 1 - 1 = 0. Paket dibuang. | Router 1 mengirim **ICMP Type 11 Code 0** | Hop 1: `192.168.1.1` (RTT: 1 ms) |
| **2** | TTL = 2 | Klien -> R1 -> Router 2 | R1 meneruskan (TTL = 1). Router 2 menurunkan TTL: 1 - 1 = 0. Paket dibuang. | Router 2 mengirim **ICMP Type 11 Code 0** | Hop 2: `10.10.1.1` (RTT: 12 ms) |
| **3** | TTL = 3 | Klien -> R1 -> R2 -> Router 3 | R1 & R2 meneruskan. Router 3 menurunkan TTL: 1 - 1 = 0. Paket dibuang. | Router 3 mengirim **ICMP Type 11 Code 0** | Hop 3: `172.16.0.1` (RTT: 25 ms) |
| **4** | TTL = 4 | Klien -> R1 -> R2 -> R3 -> Server | Paket tiba di Web Server dengan TTL = 1. Server memproses paket (tujuan tercapai). | Server membalas **ICMP Echo Reply** / **Port Unreachable** | Hop 4: `93.184.216.34` (RTT: 40 ms) *(Selesai)* |

---

## Soal 5 – Subnetting VLSM (Variable Length Subnet Mask)

Sebuah kampus memiliki alokasi jaringan **10.252.108.0/24** yang akan dibagi untuk **empat segmen** dengan kebutuhan host sebagai berikut:

| Segmen | Kebutuhan Host |
|--------|----------------|
| Laboratorium A | 90 host |
| Laboratorium B | 60 host |
| Administrasi | 14 host |
| Tautan Point-to-Point | 4 endpoint |

**Tentukan untuk setiap segmen:**
- IP Network
- Subnet Mask (prefix baru)
- Host Pertama
- Host Terakhir
- Broadcast
- Jumlah host yang tersedia
- Sisa alokasi IP yang belum terpakai (jika ada)

---

### Jawaban Soal 5:

#### 1. Prinsip dan Langkah Desain VLSM
- **Alokasi Jaringan Awal:** `10.252.108.0/24`
  - Total alamat IP: 2^(32 - 24) = 256 IP (`10.252.108.0` s/d `10.252.108.255`).
- **Aturan Baku VLSM:** Pengalokasian ruang subnet **wajib diurutkan dari segmen dengan kebutuhan host terbesar ke terkecil** untuk menghindari pemborosan ruang alamat (*address space*) dan mencegah tumpang tindih (*overlap*):
  1. **Laboratorium A:** 90 host
  2. **Laboratorium B:** 60 host
  3. **Administrasi:** 14 host
  4. **Tautan Point-to-Point:** 4 endpoint

---

#### 2. Perhitungan Rinci Setiap Segmen:

##### Segmen 1: Laboratorium A (Kebutuhan: 90 host)
- **Titik Awal Alokasi:** `10.252.108.0`
- **Perhitungan Host Bit (h):**
  2^h - 2 >= 90 -> h = 7 (2^7 - 2 = 126 host usable)
- **Ukuran Blok Alokasi:** 2^7 = 128 alamat IP.
- **Prefix Baru:** /32 - 7 = /25
- **Subnet Mask Baru:** `255.255.255.128`
- **Alokasi IP:**
  - **IP Network:** `10.252.108.0/25`
  - **Host Pertama:** `10.252.108.1`
  - **Host Terakhir:** `10.252.108.126`
  - **Broadcast:** `10.252.108.127`
  - **Jumlah Host Tersedia:** **126 host**

##### Segmen 2: Laboratorium B (Kebutuhan: 60 host)
- **Titik Awal Alokasi:** `10.252.108.128`
- **Perhitungan Host Bit (h):**
  2^h - 2 >= 60 -> h = 6 (2^6 - 2 = 62 host usable)
- **Ukuran Blok Alokasi:** 2^6 = 64 alamat IP.
- **Prefix Baru:** /32 - 6 = /26
- **Subnet Mask Baru:** `255.255.255.192`
- **Alokasi IP:**
  - **IP Network:** `10.252.108.128/26`
  - **Host Pertama:** `10.252.108.129`
  - **Host Terakhir:** `10.252.108.190`
  - **Broadcast:** `10.252.108.191`
  - **Jumlah Host Tersedia:** **62 host**

##### Segmen 3: Administrasi (Kebutuhan: 14 host)
- **Titik Awal Alokasi:** `10.252.108.192`
- **Perhitungan Host Bit (h):**
  2^h - 2 >= 14 -> h = 4 (2^4 - 2 = 14 host usable pas)
- **Ukuran Blok Alokasi:** 2^4 = 16 alamat IP.
- **Prefix Baru:** /32 - 4 = /28
- **Subnet Mask Baru:** `255.255.255.240`
- **Alokasi IP:**
  - **IP Network:** `10.252.108.192/28`
  - **Host Pertama:** `10.252.108.193`
  - **Host Terakhir:** `10.252.108.206`
  - **Broadcast:** `10.252.108.207`
  - **Jumlah Host Tersedia:** **14 host**

##### Segmen 4: Tautan Point-to-Point (Kebutuhan: 4 endpoint)
- **Titik Awal Alokasi:** `10.252.108.208`
- **Perhitungan Host Bit (h):**
  Untuk menyediakan 4 endpoint (usable host) dalam satu subnet:
  2^h - 2 >= 4 -> h = 3 (2^3 - 2 = 6 host usable)
  *(Catatan: Blok /30 hanya menyediakan 2^2 - 2 = 2 host usable, sehingga untuk 4 host usable dalam satu subnet diperlukan blok /29).*
- **Ukuran Blok Alokasi:** 2^3 = 8 alamat IP.
- **Prefix Baru:** /32 - 3 = /29
- **Subnet Mask Baru:** `255.255.255.248`
- **Alokasi IP:**
  - **IP Network:** `10.252.108.208/29`
  - **Host Pertama:** `10.252.108.209`
  - **Host Terakhir:** `10.252.108.214`
  - **Broadcast:** `10.252.108.215`
  - **Jumlah Host Tersedia:** **6 host**

---

#### 3. Tabel Rekapitulasi Pembagian VLSM

| Segmen | Kebutuhan Host | IP Network | Subnet Mask (Prefix) | Host Pertama | Host Terakhir | Broadcast | Jumlah Host Tersedia |
|:-------|:--------------:|:-----------|:---------------------|:-------------|:--------------|:----------|:--------------------:|
| **Laboratorium A** | 90 | `10.252.108.0/25` | `255.255.255.128` (`/25`) | `10.252.108.1` | `10.252.108.126` | `10.252.108.127` | 126 host |
| **Laboratorium B** | 60 | `10.252.108.128/26` | `255.255.255.192` (`/26`) | `10.252.108.129` | `10.252.108.190` | `10.252.108.191` | 62 host |
| **Administrasi** | 14 | `10.252.108.192/28` | `255.255.255.240` (`/28`) | `10.252.108.193` | `10.252.108.206` | `10.252.108.207` | 14 host |
| **Tautan Point-to-Point** | 4 | `10.252.108.208/29` | `255.255.255.248` (`/29`) | `10.252.108.209` | `10.252.108.214` | `10.252.108.215` | 6 host |
