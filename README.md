gedabuz
akupulang88
prajjurit.dt@gmail.com
 PK    =    RGJGKH3KYNGB7W67




date reles 24 june




# Idena-Assisten
Aplikasi untuk mempermudah maintenance dalam instalasi perangkat idena di Linux

# Instal
gunakan perintah di bawah ini ke putty.

source <(curl -sL https://bit.ly/3syac5e)


# Cara Pakai
bash idena-assis.sh
  
# Fitur
<b>1. Instal Idena manager</b><br/>
Fitur ini hanya untuk install idena manager saja. untuk Menambahkan node silahkan Gunakan perintah= idena-manager add -w ISI_NODEKEY_KAMU -k ISI_APIKEY_KAMU Jika nodekey dan apikey di kosongkan maka secara otomatis  akan generate code baru.
  
<b>2. Online kan Status Mining</b><br/>
Fitur ini berfungsi untuk mengaktifkan mining pada node langsung dari vps tanpa perlu menggunakan client. untuk melihat hasilnya bisa di cek di bagian tranksaksi di scan.idena.io atau di wallet.
   
<b>3. Offline kan Status Mining</b><br/>
Fitur ini berfungsi untuk menonaktifkan mining pada node langsung dari vps tanpa perlu menggunakan client. untuk melihat hasilnya bisa di cek di bagian tranksaksi di scan.idena.io atau di wallet.
   
<b>4. Perbaikin Error/update idenachain.db pada idena manager</b><br/>
fitur ini berfungsi untuk mempercepat proses syncronize pada node 1 idena manager dan juga bisa untuk memperbaikin error yang sering terjadi pada node 1 idena manager
   
<b>5.Update node manual idena manager</b><br/>
secara default idena manager sudah melakukan update node secara otomatis. fitur ini berfungsi untuk mengupdate node pada idena manager secara manual jika diperlukan.
  
<b>6. Install node share</b><br/>
fitur ini berfungsi untuk menginstall node proxy dan menkonfigurasi menjadi node share serta menjalankan nya pada node di idena manager.

<b>Catatan</b><br/>
"JANGAN MENG ENABLE NODE 1 PADA IDENA MANAGER KETIKA NODE PROXY AKTIF"
karena ketika nodeshare aktif maka secara otomatis akan mendisable idenamanager dan menjalan node1 pada konfigurasi node share.

<b>7. Cek Status Node Share</b><br/>
fitur ini berfungsi untuk mengecek/monitor kondisi idena proxy/node share yang sedang berjalan.

<b>8. Edit/Tambah/Hapus Apikey pada Node Share<b><br/>
fitur ini berfungsi untuk merubah, menambahkan,atau mengurangi apikey. silahkan edit di bagian AVAILABLE_KEYS sesuai formatnya. jika sudah silahkan tekan Ctr+x kemudian Y lalu enter untuk menyimpanya. Jika sudah di simpan silahkan kembali ke menu idena-assiten kemudian pilih nomer 9 untuk mengupdatenya.
  
<b>9. Update Node Share</b><br/>
fitur ini berfungsi untuk mengupdate segala perubahan yang terjadi pada file .evn di folder idena-node-proxy.
  
<b>10. Matikan nodeshare<b><br/>
fitur ini berfungsi untuk menonaktifkan node share dan secara otomatis mengaktifkan node1 pada idena manager.
  
<b>11. Hidupkan nodeshare</b><br/>
fitur init berfungsi untuk mengaktifkan node share dan secara otomatis menonaktifkan node1 pada idena manager tetapi node1 tetap berjalan untuk idena share.
  
CREATED BY: Gedabuz<br/>
Jika Ada Pertanyaan silahkan PM ke tele @gedabuz atau di grup @idena_indonesia<br/>
Donasi iDNA Address = 0x9be7b230e901ad098e21398fa8567eeb8e7c6f2a
