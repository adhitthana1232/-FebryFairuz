# -FebryFairuz
Source Code jawaban UTS
package inputproduk;
import java.util.*;
public class inproduk {
public static void main(String[] args) {
		char pilih;
		char inputlihat;
		Scanner input = new Scanner(System.in);
		String no;
		String inproduk;
		String Harga;
		int Stok;
		String Deskripsi;
		String berat;
	
			while(true){
				System.out.println("Silahkan Pilih : Masukan Produk / Lihat Produk(M/L)??? ");
				inputlihat = input.next().charAt(0);
				if (inputlihat == 'M'){
				System.out.println("============================================= ");	
				no = input.nextLine();
				System.out.println("Masukan Nama Produk :");
				inproduk = input.nextLine();		
				System.out.println("Masukan Harga :");
				Harga = input.nextLine();			
				System.out.println("Masukan Deskripsi :");
				Deskripsi = input.nextLine();
				System.out.println("Masukan Berat Produk :");
				berat = input.nextLine();
				System.out.println("Masukan Stok :");
				Stok= input.nextInt();
				
				
				System.out.println("============================================= ");	
				
				System.out.println("Nama : " + inproduk);	
				System.out.println("Harga Rp : " + Harga);	
				System.out.println("Stok : "+ Stok );	
				System.out.println("Deskripsi : "+ Deskripsi);  
				System.out.println("Berat : " + berat );
				}else if (inputlihat == 'L'){
					System.out.println("Produk :");	
					System.out.println("1. Laptop Asus ROG GL55");	
					System.out.println("2. Komputer Gaming");	
					System.out.println("3. VGA GTX 1080");	
					System.out.println("4. RAM DDR4 VGEN 8GB");  
				}else{
				}
				System.out.println("============================================= ");	
				System.out.println("Pilih lagi (y/n)??? ");
					pilih = input.next().charAt(0);;
					
		}
	}
}	

