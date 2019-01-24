# bizal2
BIZAL2, 10W SSB TRANSCEIVER by BHR

Skema dan gerber bisa di download di http://s000.tinyupload.com/?file_id=85613846905423438107

https://www.facebook.com/indra.s.ekoputro/posts/10206887533970080
https://www.facebook.com/indra.s.ekoputro/posts/10211731545067330

Banyak hasil eksperimen yang tidak bisa dirilis, bukan karena hasilnya tidak baik, tetapi karena banyak alasan yang menyertai-nya, seperti memilih salah satu dari beberapa eksperiment yang saya lakukan.

Bizal2 merupakan pengembangan mainboard exciter dari Bizal sebelumnya yang menerapkan transceiver multiband (3 band).
Bizal2 dikembangkan bedasarkan parameter2 sensitifitas, selektifitas, rentang dinamika, intermodulation distortion (IMD) dan noise figure total.

Bizal2 menggunakan LO dan BFO dari Si5351. Sensitifitas dan rentang dinamika sangat tergantung dari sirkit front-end-nya.
Selektifitas tergantung dari filter-filter (BPF, Xtal filter, filter audio dsb). IMD sangat tergantung dari linieritas kerja semua sub-sub bagian-nya.
Noise figure total juga tergantung dari sirkit dam komponen2 low noise yang membangunnya.

Beberapa improvement, diantaranya :
- Front end menggunakan sirkit high dynamic range, dengan IIP3 yang tinggi (+20dbm) menggunakan transistor low noise 2N3886, jika terpaksa, bisa diganti dengan transistor medium power
- Xtal filter model Butterworth dengan riple yang kecil
- narrow IF amp pada RX dan TX
- audio filter (LPF 3khz) pada receiver maupun pada mic amplifier (TX)
- AGC dengan RF derivative
- konektor untuk BPF multiband board
- Audio out 2W (LM380)
- Rangkaian PA linear yang sederhana.

BIZAL2 adalah monoband transceiver, dan bisa dikembangkan menjadi multiband dengan menambah BPF, LPF tambahan dan band controlled-nya.

RF out sekitar 8-10W, cukup buat QRP atau sebagai pendorong PA linear sampai 100W.

Bagi temen2 yang berminat untuk bereksperiment dengan BIZAL2, tinggal download skema di atas, pelajari dengan baik. Jika berminat, bisa kirim gerber ke China, salah satunya JLCPCB. Ukuran pcb persis 10cm x 10cm.

