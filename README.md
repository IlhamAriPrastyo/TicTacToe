Ilham Ari Prastyo

5311421014

# TicTacToe
pada program tictactoe terdiri dari 6 program berbeda yang dijadikan dalam satu folder atau satu paket.
pada program enumerasi terdiri dari 3program sebagai keadaan, ada gamestate.java seed.java dan state.java yang digunakan sebagai kondisi.

pada gamestate.java terdapat kondisi saat playing, cross win dan nought win.

pada state.java untuk mengidentifikasi berbagai keadaan permainan, seperti "PLAYING", "DRAW", "CROSS_WON", atau "NOUGHT_WON". 

pada seed.java terdiri dari lambang dari tictactoenya yaitu cross dan nought dan kondisi kosong digunakan untuk mewakili pemain (CROSS atau NOUGHT) dan isi sel pada papan permainan (CROSS, NOUGHT, atau NO_SEED)

Program menggunakan kelas GamePanel yang merupakan JPanel khusus untuk menggambar papan permainan dan simbol CROSS atau NOUGHT di dalam sel. Fungsi paintComponent() digunakan untuk menggambar seluruh elemen permainan, termasuk sel, garis pembatas, simbol pemain, dan pesan status.

untuk membuat papan, dibuat pada board.java untuk membentuk papan 3x3 yang akan diisi oleh kondisi x dan o tadi.

untuk cell.java digunakan untuk mengisi seed atau kotak kosong pada papan, Saat permainan dimulai (dalam konstruktor), papan permainan (array 2D board) diinisialisasi dengan seluruh sel yang berisi NO_SEED. Pemain yang pertama kali bermain adalah CROSS, dan permainan dimulai dalam keadaan "PLAYING".

![image](https://github.com/IlhamAriPrastyo/TicTacToe/assets/148432155/3a77a9b5-1e6a-4926-a64d-5366022a41bf)

papan tersebut nantinya akan diisi dari seed.java yaitu x dan o.

![image](https://github.com/IlhamAriPrastyo/TicTacToe/assets/148432155/c5c9196e-9b1d-42a2-a732-00454a1c6a75)

untuk main() adalah titik awal dari program. Program GUI dijalankan dalam EDT (Event Dispatch Thread) untuk keamanan thread. Itu menginstansiasi objek GameMain, yang pada gilirannya akan memicu proses inisialisasi dan menjalankan permainan.

Lalu StatusBar digunakan untuk menampilkan status permainan kepada pemain, termasuk giliran siapa saat ini dan hasil permainan (seri, X menang, atau O menang). Jika ada pemenang, status permainan diperbarui sesuai (CROSS_WON atau NOUGHT_WON).Jika permainan berakhir seri, status permainan diubah menjadi DRAW.
