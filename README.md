#step1 installasi
apt update && apt upgrade

pkg install git

pkg install python2

pip2 install mechanize 

pip2 install requests 

git clone https://github.com/mapelvader/bot_comment_facebook

cd botkom-facebook

python2 komen.py

#step2 command

KODE:	FUNGSI:

get_data	 mengambil semua data teman

get_info	 menampilkan data temanmu

dump_id	 mengambil semua id daftar teman

dump_phone	 mengambil semua nomor ponsel daftar teman

dump_mail	 mengambil semua email daftar teman

dump_<id>_id	mengambil semua id temanmu <spesifik>

token	 membuat akses token

cat_token 	melihat token yg tersimpan

rm_token	 menghapus token yg tersimpan

bot	 membuka f bot

clear	membersihkan terminal

about	menampilkan informasi tentang program ini

exit keluar program
