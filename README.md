1. Login ke debian dengan menggunakan user root lalu setting IP untuk server dengan mengetikan perintah nano/etc/network/interfaces. 
2. Restart IP dengan perintah /etc/unit.d/networking restart, lalu cek IP sudah berhasil atau belum dengan perintah ip a.
3. jika berhasil selanjutnya masukan DVD 2 dan instal bind9, dengan perintah apt-get install bind9, jika ada pertanyaan [y/n] maka klik y kemudian enter.
4. jika terjadi error ketikan perintah apt--fix-broken install. Jika tidak terjadi error berarti instalasi berhasil, kemudian ada perintah untuk mrmasukan DVD binary 1 maka masukan DVD binary 1 kemudian enter.  
5. untuk memastikan instalasi sudah berhasil atau belum ketikan kembali perintah apt-get install bind9, jika ada keterangan 0 upgrade, 0 newly installed, 0 to remove, and 0 not upgraded. maka instalasi berhasil. 
 6. lalu masuk ke directory bind dengan perintah cd/etc/bind. Lalu konfigurasi pada bagian file forward, file reverse, named.conf.options, named.conf.local, lalu etc/resolv.conf.
    
