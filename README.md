# Dokumentasi-Installasi-Tools
Pertama kita harus install wsl nya terlebih dahulu, dengan cara buka powershell administrasion kemudian ketik command "wsl --install"
![install wsl](https://user-images.githubusercontent.com/114826232/193461911-a0e8c874-11a4-4e54-ada3-b97aa6d4de2b.png)
Setelah itu lalu kita update wsl nya ke versi 2 dengan cara ketikan command "wsl -set-default-version 2"
![wsl install - Copy (2)](https://user-images.githubusercontent.com/114826232/193462881-5275d257-bf22-4e67-9dd2-bed49ad2c2a1.png)
Setelah wsl versi 2 sudah terupdate dengan sukses,kemudian kita install ubuntu versi 20-04, dengan command "wsl --install -d Ubuntu-20.04" dan tunggu sampai terdapat keterangan "Launching Ubuntu 20.04 LTS
![wsl install - Copy (3)](https://user-images.githubusercontent.com/114826232/193463044-358a76c8-61d1-4b32-9410-41d2dfff42e7.png)
Kemudian setelah ubuntu selesai terinstall, ketikan command dengan "ubuntu2004 config --default-user root"
![wsl install - Copy (4)](https://user-images.githubusercontent.com/114826232/193463521-6b7fa77f-466b-4f91-a2bb-2fc008714704.png)
Selanjutnya kita buka apk Ubuntu 20.04 yang sudah terinstall, dan kemudian kita masukan username dan password untuk ubuntu nya tersebut. Dan perlu diingat bahwa saat kita mengisi password, tampilan password itu transparan.
![install ubuntu dan username,password](https://user-images.githubusercontent.com/114826232/193463679-b6774c81-0871-440f-92f0-4dd9e9c8d87e.png)
Sebelum lanjut ke langkah selanjutnya, pastikan turn windows features on or off buat ngecek apa windows subsystem for linux sama virtual machine platform sudah di centang 
![WhatsApp Image 2022-10-01 at 22 01 59](https://user-images.githubusercontent.com/114826232/193463954-30e0fcae-afeb-4d0f-b1e3-8351643dacfd.jpeg)
Setelah itu kita download firacode.zip di https://shared.djambred.my.id/Tools/ untuk mengganti font kita nanti
![firacode](https://user-images.githubusercontent.com/114826232/193464229-0271c8d5-f28f-4787-9188-8d93093163b7.png)
Kemudian buka file rar nya dan cari fira code retina nerd font complete windows compatible.ttf dan kemudian install
Setelah kita install fira code nya, lalu kita buka terminal pada windows, jika tidak terdapat terminal, maka install terlebih dahulu di microsoft store
![download terminal](https://user-images.githubusercontent.com/114826232/193464475-0208fc42-904a-4dfd-a833-8ff3c8481aae.png)
Jika terminal sudah selesai terinstall, klik tanda panah bawah dan kemudian klik setting
![hh (2)](https://user-images.githubusercontent.com/114826232/193464678-be630b19-be27-48c9-bd75-396f944543f1.png)
Pada tampilan setting kita klik "when terminal starts" kemudian pilih "Ubuntu-20.04"
![setting ubuntu](https://user-images.githubusercontent.com/114826232/193464804-6c09687e-9b36-4347-aa05-9afd5811b04c.png)
Jika sudah maka kita lanjut pilih "Ubuntu-20.04" yang ada dibawah sebelah kiri, kemudian klik "Font face" dan pilih "Firacode NF Retina" kemudian save dan close
![setting firacode](https://user-images.githubusercontent.com/114826232/193465036-b4ff1948-5d35-4657-89a3-1566d502ff5c.jpg)
Kemudian buka terminal lagi dan lakukan update ubuntu dengan command "apt update"
![update ubuntu](https://user-images.githubusercontent.com/114826232/193465163-b7149d2a-7643-4f05-b879-706fbba1ecf0.png)
Dan ini tampilan setelah selesai di update
![prosess update](https://user-images.githubusercontent.com/114826232/193465286-8c6ab8ec-58ec-463b-998e-0dfeffc45ccd.png)
Jika telah selesai di update, kemudian buka  https://github.com/ohmyzsh/ohmyzsh
![sch](https://user-images.githubusercontent.com/114826232/193465420-b3e5035d-ed7a-4597-8cb4-4e41b0f8a529.png)
Kemudian di terminal, ketikan apt install zsh trus jika terdapat tulisan "do you want to continue" klik "Y"
![prosess zsh](https://user-images.githubusercontent.com/114826232/193465528-e3ae8933-2ff3-4238-ade6-ac53f62fb179.png)
Setelah itu tulis sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh), kemudian enter dan klik "Y"
![prosess zsh](https://user-images.githubusercontent.com/114826232/193465528-e3ae8933-2ff3-4238-ade6-ac53f62fb179.png)
Selanjutnya ketik nano /root/.zshrc
![zsh](https://user-images.githubusercontent.com/114826232/193465869-2dadebde-f0f4-4754-9a6c-9b8c9e56a5ca.png)
Dan selanjutnya tulisan "zsh_theme" diganti dengan kata "agnoster" kemudian tekan "Ctrl + X" dan enter
![nano](https://user-images.githubusercontent.com/114826232/193466060-0e50ad1d-f2ec-4c19-9094-9ff0e4703048.png)
![nano lagi](https://user-images.githubusercontent.com/114826232/193466084-c49085ef-432e-400c-8d80-13dcf7008098.png)
Selanjutnya ketik "source /root/.zshrc"
![source root](https://user-images.githubusercontent.com/114826232/193466304-c3254363-4ea1-4350-afc6-3a6af5972758.jpg)
Kemudian ketik "git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting"
![git clone](https://user-images.githubusercontent.com/114826232/193466385-5fa6dcfc-d5bd-4d55-9b74-620b49df13d7.png)
Setelah itu kita akan mengetahui font atau tulisan kita salah, font tersebut akan berwarna merah, tetapi benar maka akan berwarna hijau
![nano root](https://user-images.githubusercontent.com/114826232/193466501-af77bcb8-dc54-4cad-9058-08d0b8f89cf4.png)
Jika sudah maka kita langsung saja daftar github sebagai student
![daftar github](https://user-images.githubusercontent.com/114826232/193466617-0747b77a-59a5-4e1e-ae55-a689313985eb.png)
Masukan email dan password
![daftargithub2](https://user-images.githubusercontent.com/114826232/193466640-48d7c9b3-7c3e-40c7-b52f-664d39cf918e.png)
JIka telah selesai daftar github, maka buka kembali terminal nya dan ketikan command "ssh-keygen"
![ssh keygen](https://user-images.githubusercontent.com/114826232/193466699-a0ad4e50-b850-44c4-af57-875d9f6846f9.png)
Setelah itu ketikan command "cat /root/.ssh/id_rsa.pub"
Selanjutnya buka kembali github untuk mendapatkan token access, pastikan token tersebut disimpan dalam notepad 
![token access](https://user-images.githubusercontent.com/114826232/193466836-e0350a3a-16a7-4de4-83c1-e56f7f40c943.png)
Kemudian kita akan mencoba membuat program dengan judul bahasa_pemrograman
![mdkir contoh tulisan salah](https://user-images.githubusercontent.com/114826232/193466888-a3c8c151-3f99-46f8-94c4-c0071cebc8cc.png)
Maka otomatis akan masuk ke visual code, kemudian lakukan penginstallan pada visual code. Jika python sudah terinstall, tidak perlu lakukan penginstallan tetapi belum lakukan penginstallan setelah install visual code
![visual code install](https://user-images.githubusercontent.com/114826232/193467011-4020c708-bede-45fc-bf6a-c350bcda6123.png)
Kemudian buat contoh program "Print ("hallo")
![contoh](https://user-images.githubusercontent.com/114826232/193467086-22d3ce06-2cdf-40f7-9eef-2cbe1374d47f.png)
Setelah itu buka terminal dan ikuti perintah seperti pada gambar dan kemudian masukan token access home github kita
![input](https://user-images.githubusercontent.com/114826232/193467148-da8a2083-0ff7-4276-a251-7789333b2535.png)
Jika sudah cek repositoris, maka program yang kita buat sudah terupload di github
![hasil](https://user-images.githubusercontent.com/114826232/193467494-314e6e2a-9a11-4335-9145-2a234c579e80.png)



