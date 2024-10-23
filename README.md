# praktikum-pert-5
# mahasiswa.java

    public class Mahasiswa extends Manusia {
    String nim;
    String jurusan;

    public Mahasiswa(String nama, String jenisKelamin, int umur, String alamat, String nim, String jurusan) {
        super(nama, jenisKelamin, umur, alamat);
        this.nim = nim;
        this.jurusan = jurusan;
    }

    // Getter dan Setter untuk Mahasiswa
    public String getNim() {
        return nim;
    }

    public void setNim(String nim) {
        this.nim = nim;
    }

    public String getJurusan() {
        return jurusan;
    }

    public void setJurusan(String jurusan) {
        this.jurusan = jurusan;
    }
    }
![code100](https://github.com/user-attachments/assets/087e42fb-4e6f-4bed-8077-0d58a7d449a4)

# mahasiswaberaksi.java

    public class MahasiswaBeraksi {
       public static void main(String[] args) {
        // Membuat objek Mahasiswa dengan menggunakan konstruktor
        Mahasiswa anton = new Mahasiswa("Gusti Ardhya Nanda Fahreza", "Laki-Laki", 19, "Cikarang Utara", "312310624", "Teknik Informatika");

        // Memanggil metode untuk mencetak informasi
        anton.cetakInfo();
        System.out.println("NIM             : " + anton.getNim());
        System.out.println("Jurusan         : " + anton.getJurusan());
    }
    }

![code101](https://github.com/user-attachments/assets/7e065034-580d-482b-8857-90831abc2e69)

# manusia.java

    public class Manusia {
    String nama;
    String jenisKelamin;
    int umur;
    String alamat;

    // Konstruktor
    public Manusia(String nama, String jenisKelamin, int umur, String alamat) {
        this.nama = nama;
        this.jenisKelamin = jenisKelamin;
        this.umur = umur;
        this.alamat = alamat;
    }

    // Getter dan Setter methods
    public String getNama() {
        return nama;
    }

    public void setNama(String nama) {
        this.nama = nama;
    }

    public String getJenisKelamin() {
        return jenisKelamin;
    }

    public void setJenisKelamin(String jenisKelamin) {
        this.jenisKelamin = jenisKelamin;
    }

    public int getUmur() {
        return umur;
    }

    public void setUmur(int umur) {
        this.umur = umur;
    }

    public String getAlamat() {
        return alamat;
    }

    public void setAlamat(String alamat) {
        this.alamat = alamat;
    }

    public void cetakInfo() {
        System.out.println("Nama            : " + this.nama);
        System.out.println("Jenis Kelamin   : " + this.jenisKelamin);
        System.out.println("Umur            : " + this.umur);
        System.out.println("Alamat          : " + this.alamat);
    }
    }
![code102](https://github.com/user-attachments/assets/84a2e7c0-bf1f-4c00-b046-f74277ede225)

# output

![Screenshot (162)](https://github.com/user-attachments/assets/805f4249-e59d-4412-9900-a540afe5f8a0)

# pegawai.java
![code103](https://github.com/user-attachments/assets/32fb5ec3-9889-405a-b955-72c6bedfa318)

# output
![Screenshot (163)](https://github.com/user-attachments/assets/3a0b7dc9-eb10-44ce-8fa4-a5c32ad0d6fa)






