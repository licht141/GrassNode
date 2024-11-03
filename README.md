## Grass Node
- Dibuat untuk Linux cli agar dapat menggunakan grass dengan mudah
## Fitur
- proxy
- multi threading
## Installasi 
-     git clone https://github.com/licht141/GrassNode/
-     cd GrassNode
-     pip3 install -r requirements.txt
## Configurasi
-
pada configs.json isi user_id dengan user_id yang di dapatkan dari grass 
caranya adalah dengan membuka dashboard grass lalu membuka console atau developer mode lalu paste kode di bawah ini
-     localStorage.getItem('userId')
lalu pada proxy isi dengan format protocol://ip:port
dan jalankan dengan perintah
-     python3 main.py    
