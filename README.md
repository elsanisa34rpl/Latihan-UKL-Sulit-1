# Latihan-UKL-Sulit-1

Bagian 1 

    public class Mavenproject3 {
    static double hitungRataRata(double[] nilai, int jumlahSiswa) {
        double total = 0;
        for (int i = 0; i < jumlahSiswa; i++) {
            total += nilai[i];
        }
        return total / jumlahSiswa;
    }

*Fungsi ini bernama hitungRataRata, dan tujuannya adalah menghitung nilai rata-rata dari sekumpulan nilai siswa.*

         public static void main(String[] args) {
         Scanner input = new Scanner(System.in);

        System.out.print("Masukkan jumlah siswa: ");
        int jumlahSiswa = input.nextInt();
        double[] nilai = new double[jumlahSiswa];

        // Input nilai setiap siswa
        for (int i = 0; i < jumlahSiswa; i++) {
            System.out.print("Masukkan nilai siswa ke-" + (i + 1) + ": ");<img width="1804" height="943" alt="Screenshot 2025-11-04 183736" src="https://github.com/user-attachments/assets/05b2df9e-2181-4dc3-b756-efc2500f7cd2" />

            nilai[i] = input.nextDouble();
        }
*Program tersebut digunakan untuk meminta pengguna memasukkan jumlah siswa dan nilai masing-masing siswa, lalu menyimpan nilai-nilai tersebut
ke dalam array untuk diolah lebih lanjut (misalnya menghitung rata-rata).*


       // Panggil fungsi untuk menghitung rata-rata
        double rataRata = hitungRataRata(nilai, jumlahSiswa);

        // Cetak hasil
        System.out.printf("\nNilai rata-rata dari %d siswa adalah: %.2f\n", jumlahSiswa, rataRata);
    
    }
    }

Potongan program tersebut berfungsi untuk **memanggil fungsi `hitungRataRata`** guna menghitung rata-rata nilai seluruh siswa, kemudian **menampilkan hasil rata-rata tersebut ke layar**
dalam format dua angka di belakang koma.

Screenshot hasil program:

<img width="1903" height="916" alt="Screenshot 2025-11-04 231934" src="https://github.com/user-attachments/assets/1f8ac902-56c7-4384-9661-8f2770217040" />

