#include <iostream> 
using namespace std; 
struct buku 
{
	int kodeB,sewa,stock;
	char judul[20];
	int b;
}buku[100]; 
struct pinjam 
{
	int kodepinjam,d,kB,tglpin,tglbalik,dipinjem;
	char namap[40];
	char alamat[40];
	char status;
}pinjembuku[100]; 
