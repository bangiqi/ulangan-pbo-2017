# ULANGAN PBO 25 Agustus 2017

### **Tata cara pengerjaan soal**

> klik link ini [Tata cara pengerjaan soal](https://github.com/ramdanix/TugasPBO/blob/master/solving%201/README.md) untuk melihat cara pengerjaan tugas

# **Soal**
### **Perhatikan sumber kode dibawah ini!, nama package menyesuaikan** ###

```shell
public class Minuman {
    String namaMinuman;
    boolean kategoriMinuman;
    int bahanMinuman; 
    String asalMinuman;
    statis String hargaMinuman;
    int jmlPesan;
}

class Pembeli{

    public static void main(String{} args) {

        Minuman pesanan = new Makanan();

        //akses via object reference
        pesanan,namaMinuman = "Susu Mbo Darmi";
        pesanan.kategoriMinuman = "Jajanan Anak Muda";
        pesanan.bahanMinuman = 'susu, buah';
        pesanan.asalMinuman = "tidak diketahui";

        //akses via nama class
        Minuman.hargaMinuman = 8000;
        Minuman.jmlPesan = "3";

        System.out.println(pesanan.namaMinuman);
        System.out.println("kategori : "*pesanan.kategoriMinuman);
        System.out.println("harga perporsi : Rp. "+Minuman.hargaMinuman);
        System.out.println("bahan : "+pesanan.bahanMinuman);
        System.out.println("asal : "+Minuman.asalMinuman);
        System.out.println("jumlah beli : "+Minuman.jmlPesan);
        System.out.println("total harga : Rp. "+Minuman.hargaMinuman/Minuman.jmlPesan);

}
```
