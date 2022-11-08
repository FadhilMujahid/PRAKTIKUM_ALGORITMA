#include <iostream>
#include <string>
using namespace std;

int main()
{
	int kamar, harga, lama, bayar, i;
	string nkamar, a, jawab;

    cout<<"PRAKTIKUM ALGORITMA 25-10-2022"<<endl;
    cout<<"Nama  : Fadhil Mujahid"<<endl;
    cout<<"Prodi : Informatika"<<endl<<endl;
	cout<<"SISTEM INFORMASI PENYEWAAN KAMAR DI HOTEL MUMU NONO"<<endl;
	cout<<endl;
	do {
	cout<<"No   Jenis Kamar          Harga "<<endl;
	cout<<"1.   Standar              Rp:500.000"<<endl;
	cout<<"2.   Superior             Rp:1.000.000"<<endl;
	cout<<"3.   Deluxe               Rp:1.500.000"<<endl;
	cout<<"---------------------------------------"<<endl;
	cout<<endl;
	
	cout<<"Pilh Jenis kamar : ";
	cin>>kamar;
	
	if (kamar==1)
	{
		harga=500000;
		nkamar="Standar";
	}
	else if (kamar==2)
	{
		harga=1000000;
		nkamar="Superior";
	}
	else if (kamar==3)
	{
		harga=1500000;
		nkamar="Deluxe";
	}
	
	cout<<"Kamar yang anda pilih adalah kamar "<<nkamar<<" dengan harga Rp:"<<harga<<"/Hari"<<endl;
	cout<< "" <<endl;
	cout<<"Berapa lama anda ingin menyewa kamar tersebut : ";
	
	cin>>lama;
   
	bayar=lama*harga;
	
	cout<<"Jenis kamar pilihan anda : "<<nkamar<<endl;
	cout<<"Lama penyewaan anda "<<lama<<" hari"<<endl;
	cout<<""<<endl;
	cout<<"Total harga penyewaan yang harus anda bayar adalah  Rp; "<<bayar<<endl;
	cout<< "" <<endl;
	cout << "Apakah anda ingin memesan kamar lainnya? (ya/tidak)" << endl;
	cin >> jawab;
	i++;
	
	}
while(jawab=="ya");
    
cout << "terimakasih telah memilih pelayanan di hotel kami" << endl;
    
    //if…else digunakan untuk mengecek kondisi sebuah pernyataan dan menghasilkan output sesuai kondisi dari pernyataan tersebut, sedangkan do…while digunakan untuk mengulangi (looping) sebuah output jika kondisi dari pernyataannya masih benar.
return 0;
}
