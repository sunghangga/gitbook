# Beli dalam Satuan yang Berbeda dengan Penjualan

Saat membeli suatu produk, mungkin vendor menggunakan satuan ukuran yang berbeda dengan yang digunakan saat penjualan. Hal ini dapat menyebabkan kebingungan antara penjualan dan pembelian. Mengonversi pengukuran secara manual setiap saat juga memakan waktu. Fitur ini dapat mengonfigurasi produk satu kali dan secara otomatis menangani konversinya. Ikuti langkah berikut untuk lebih jelasnya.

1. Masuk ke halaman **Stok Persediaan > Konfigurasi > Pengaturan**.
2. Pada bagian **Produk**, centang **Satuan** untuk mengaktifkan fitur satuan pada produk. Llau simpan pengubahan

<figure><img src="../../../.gitbook/assets/image (1).png" alt=""><figcaption><p>Opsi Satuan pada Produk</p></figcaption></figure>

3. Buat baru kategori satuan pada halaman **Stok Persediaan > Konfigurasi > Kategori Satuan**.
4. Pilih **Baru** untuk membuat kategori baru untuk satuan, dalam hal ini akan dibuat kategori satuan baru untuk kain.
5. Pada **Unit of Measure Category** masukkan nama dari kategori, pada tabel satuan masukkan satuan yang termasuk pada kategori tersebut, seperti contoh berikut.

<figure><img src="../../../.gitbook/assets/image (4).png" alt=""><figcaption><p>Kategori Satuan</p></figcaption></figure>

Saat menambahkan satuan perlu memasukkan **Rasio** antara satuan dasar dan satuan kedua. Jika satuan kedua lebih kecil maka rasionya harus lebih besar dari 1. Jika satuan kedua lebih besar maka rasionya harus lebih kecil dari 1. Jika satu gulungan memliki luas 100 meter persegi maka rasionya harus disetel ke 100.

6. Selanjutnya menuju halaman produk, pilih produk yang ingin diubah satuannya, dalam hal ini satuan yang digunakan untuk penjualan adalah meter persegi dan untuk pembelian menggunakan gulungan.

<figure><img src="../../../.gitbook/assets/image (5).png" alt=""><figcaption><p>Atur Satuan Produk</p></figcaption></figure>

{% hint style="info" %}
Dalam memilih satuan, pastikan **Satuan** dan **Purchase UoM** ada pada kategori satuan yang sama.
{% endhint %}

7. Jika berhasil maka saat melakukan penjualan akan dijual per meter persegi dan saat melakukan pembelian akan dibeli per gulungan.

<figure><img src="../../../.gitbook/assets/image (6).png" alt=""><figcaption><p>Proses Pembelian</p></figcaption></figure>

Terlihat saat melakukan pembelian produk akan otomatis memilih satuan **"Gulungan"** dan total pembelian akan terkakulasi sesuai rasio yang telah diatur sebelumnya. Pada satuan produk (untuk pelanggan) berupa meter persegi dengan rasio 100, yang artinya satu gulungan sama dengan 100 meter persegi. Maka pada order pembelian, **Harga Satuan** didapat dari **100 (radio meter persegi) x 5.000 (harga modal) = 500.000**.
