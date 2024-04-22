#Reflection 1
1. Ada 5 data yang di publish oleh program ke message broker dalam satu kali run. Hal ini dapat dilihat dari function main yang melakukan pemanggilan publish_event() sebanyak 5 kali, dimana tiap kali mengirimkan satu data.

2. Program subscriber dan publisher memiliki url yang sama karena menggunakan satu tempat yang sama untuk berkomunikasi. Perbedaannya adalah publisher akan mengirimkan data ke message queue sedangkan subscriber sebagai listener yang mengambil data dari message queue. Jika url nya berbeda, keduanya tidak akan bisa berkomunikasi.