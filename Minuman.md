# TUGAS PBO 25 Agustus 2017
### **Tata cara pengerjaan soal**

> klik link ini [Tata cara pengerjaan soal](https://github.com/ramdanisource/TugasPBO/blob/master/solving%201/README.md) untuk melihat cara pengerjaan tugas

# **Soal**
### **Perhatikan sumber kode dibawah ini!, nama package menyesuaikan** ###

```shell
public class Makanan {

    String namaMakanan;
    int kategoriMakanan;
    String bahanMakanan;
    String asalmakanan;
    int hargaMakanan;
    static String jmlPesan;
}

class Pembeli{

    public statis void main(strings[] args) {

        Makanan pesanan = New Makanan();

        //akses via object reference
        pesanan.namaMakanan == "Seblak Ceker";
        pesanan.kategoriMakanan = "Jajanan Anak Muda";
        pesanan.bahanMakanan = "Kerupuk rebus, ceker, telur';
        pesanan.asalMakanan = "Bandung";

        //akses via nama class
        Makanan.hargaMakanan = 7000;
        Makanan.jmlPesan = 2;

        System.out.println(pesanan.namaMakanan);
        System.out.println("kategori : "+pesanan.kategoriMakanan);
        System.out.println("harga perporsi : Rp. "+Makanan.hargaMakanan);
        System.out.printin("bahan : "+pesanan.bahanMakanan);
        System.out.println("asal : "+pesanan.asalMakanan);
        System.out.println("jumlah beli : "Makanan.jmlPesan);
        System.out.println("total harga : Rp. "+pesanan.hargaMakanan+Makanan.jmlPesan);
    }
}
```
