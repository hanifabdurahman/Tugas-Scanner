# Tugas-Scanner
  public static void main (String[]args){         // deklarasi variabel         String nidn,nama,alamat;         int jum_penelitian;         // membuat scanner baru         Scanner keyboard = new Scanner(System.in);         // menampilkan output ke user         System.out.println("Input Data Penelitian Dosen Univrab");         System.out.println("___________________________________");         System.out.print("NIDN :");         // menggunakan scanner dan menimpan apa yang diketik di variabel nidn         nidn = keyboard.nextLine();         System.out.print("Nama Dosen :");         // menggunakan scanner dan menimpan apa yang diketik di variabel nidn         nama = keyboard.nextLine();         // tampilkan output         System.out.print("Alamat Dosen :");         // menggunakan scanner         alamat = keyboard.nextLine();         // menggunakan scanner         System.out.print("Jumlah Penelitian :");         jum_penelitian = keyboard.nextInt();         // menampilkan apa yang sudah di simpan di variabel         System.out.println("Hasil Penginputan Data Penelitian Dosen Univrab");         System.out.println("_______________________________________________");         System.out.println("NIDN :"+ nidn);         System.out.println("Nama Dosen :"+ nama);         System.out.println("Alamat Dosen :"+ alamat);         System.out.println("Jumlah Penelitian :"+ jum_penelitian);        }  }
