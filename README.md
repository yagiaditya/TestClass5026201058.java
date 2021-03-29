# TestClass5026201058.java
Tugas 3
package sample;

import java.util.Scanner;

public class ProcessAName5026201058 {
    public static void main(String [] args) {
        String NAMA,NRP,JURUSAN;
        Scanner keyboard = new Scanner (System.in);

        System.out.println("_____Biodata Mahasiswa_____");

        System.out.println("Input Nama");
        NAMA = keyboard.nextLine();

        System.out.println("Input NRP");
        NRP = keyboard.nextLine();

        System.out.println("Input Jurusan");
        JURUSAN = keyboard.nextLine();

        System.out.println("----------------");
        System.out.println("NAMA :"+ NAMA);
        System.out.println("NRP :"+ NRP);
        System.out.println("JURUSAN :"+ JURUSAN);

    }
}
