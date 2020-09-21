#include <iostream>
#include <string>

using namespace std;

int main (){
	string nama;
	string alamat;
	string npm;
	string jurusan;
	
	cout<<"Masukan Data Berikut : "<<endl<<endl;
	cout<<"Nama    : ";
	getline (cin, nama); 
	 
	cout<<"Alamat  : ";
	getline (cin, alamat); 
	 
	cout<<"NPM     : ";
	getline (cin, npm); 
	 
	cout<<"Jurusan : ";
	getline (cin, jurusan); 
	
	cout<<endl;
	cout<<"DATA MAHASISWA"<<endl; 
	cout<<"------------------------------"<<endl;
	
	cout<<"Nama    : "<<nama<<endl;
	cout<<"Alamat  : "<<alamat<<endl;
	cout<<"NPM     : "<<npm<<endl;
	cout<<"Jurusan : "<<jurusan<<endl;

}
