# Project_UAS

| NAMA  :| Taufik Hidayat |
| --- | --- |
| NIM   :| 312310576 |
| KELAS :| TI.23.A6 |
| DOSEN :| Agung Nugroho,S.Kom.,M.Kom |

# Program Kasir Kantin
- Dibawah adalah untuk method menampilkan daftar menu

```
# fungsi untuk daftar menu makanan
def makanan():
    global total_makan, jumlah_porsi, nama_makanan

# fungsi untuk daftar menu minuman
def minuman():
    global total_minum, jumlah_gelas, nama_minuman
print("|================================|")
print("|       Program Mesin Kasir      |")
print("|================================|")
print("|     : Pilih Menu Makanan :     |")
print("|================================|")
print("|1. Nasi Goreng         Rp.12000 |")
print("|2. Ayam Geprek         Rp.12000 |")
print("|3. Mie Goreng/Rebus    Rp.5000  |")
print("|4. ketoprak            Rp.7000  |")
print("|5. Ikan Bakar          Rp.20000 |")
print("|================================|")
menu_makanan = int(input(" Pilih Menu (1/2/3/4/5) : "))
jumlah_porsi = int(input(" Berapa Porsi : "))
```
- fungsi if, ketika user memilih menu makanan yang ada, maka program dapat langsung mengeksekusi nya
```
if menu_makanan == 1:
    total_makan = jumlah_porsi * 12000
    print(" Nasi Goreng",jumlah_porsi," Porsi : Rp.",total_makan)
    nama_makanan = (" Nasi Goreng")
elif menu_makanan == 2:
    total_makan = jumlah_porsi * 12000
    print(" Ayam Geprek",jumlah_porsi," Porsi : Rp.",total_makan)
    nama_makanan = (" Ayam Geprek")
elif menu_makanan == 3:
    total_makan = jumlah_porsi * 5000
    print(" Mie Goreng/Rebus",jumlah_porsi," Porsi : Rp.",total_makan)
    nama_makanan = (" Mie Goreng/Rebus")
elif menu_makanan == 4:
    total_makan = jumlah_porsi * 7000
    print(" Ketoprak",jumlah_porsi," Porsi : Rp.",total_makan)
    nama_makanan = (" Ketoprak")
elif menu_makanan == 5:
    total_makan = jumlah_porsi * 20000
    print(" Ikan Bakar",jumlah_porsi," Porsi : Rp.",total_makan)
    nama_makanan = (" Ikan bakar")
else:
    print(" Piihan Tidak Tersedia")
```
- Sedangkan disini list menu minuman
```
if menu_makanan == 1:
    total_makan = jumlah_porsi * 12000
    print(" Nasi Goreng",jumlah_porsi," Porsi : Rp.",total_makan)
    nama_makanan = (" Nasi Goreng")
elif menu_makanan == 2:
    total_makan = jumlah_porsi * 12000
    print(" Ayam Geprek",jumlah_porsi," Porsi : Rp.",total_makan)
    nama_makanan = (" Ayam Geprek")
elif menu_makanan == 3:
    total_makan = jumlah_porsi * 5000
    print(" Mie Goreng/Rebus",jumlah_porsi," Porsi : Rp.",total_makan)
    nama_makanan = (" Mie Goreng/Rebus")
elif menu_makanan == 4:
    total_makan = jumlah_porsi * 7000
    print(" Ketoprak",jumlah_porsi," Porsi : Rp.",total_makan)
    nama_makanan = (" Ketoprak")
elif menu_makanan == 5:
    total_makan = jumlah_porsi * 20000
    print(" Ikan Bakar",jumlah_porsi," Porsi : Rp.",total_makan)
    nama_makanan = (" Ikan bakar")
else:
    print(" Piihan Tidak Tersedia")
```
- ini program struk pembeliannya
```
# proses menghitung semua harga yang harus dibayar
makanan()
minuman()
jumlah_semuanya = total_makan + total_minum

# daftar pembelian
print()
print("|================================|")
print("|         Daftar Pembelian       |")
print("|================================|")
print("| Makanan :",nama_makanan,"\t |")
print("| Porsi   : ",jumlah_porsi,"\t\t\t |")
print("| Minuman :",nama_minuman,"\t |")
print("| Gelas   : ",jumlah_gelas,"\t\t\t |")
print("|================================|")
print("|    Jadi Yang Harus Di Bayar    |")
print("|================================|")
print("| Total :",jumlah_semuanya,"              |") 
print("|================================|")
print()
```
- Dibawah ini adalah kode lengkapnya
```
# fungsi untuk daftar menu makanan
def makanan():
    global total_makan, jumlah_porsi, nama_makanan

# fungsi untuk daftar menu minuman
def minuman():
    global total_minum, jumlah_gelas, nama_minuman

print("|================================|")
print("|       Program Mesin Kasir      |")
print("|================================|")
print("|     : Pilih Menu Makanan :     |")
print("|================================|")
print("|1. Nasi Goreng         Rp.12000 |")
print("|2. Ayam Geprek         Rp.12000 |")
print("|3. Mie Goreng/Rebus    Rp.5000  |")
print("|4. ketoprak            Rp.7000  |")
print("|5. Ikan Bakar          Rp.20000 |")
print("|================================|")
menu_makanan = int(input(" Pilih Menu (1/2/3/4/5) : "))
jumlah_porsi = int(input(" Berapa Porsi : "))

if menu_makanan == 1:
    total_makan = jumlah_porsi * 12000
    print(" Nasi Goreng",jumlah_porsi," Porsi : Rp.",total_makan)
    nama_makanan = (" Nasi Goreng")
elif menu_makanan == 2:
    total_makan = jumlah_porsi * 12000
    print(" Ayam Geprek",jumlah_porsi," Porsi : Rp.",total_makan)
    nama_makanan = (" Ayam Geprek")
elif menu_makanan == 3:
    total_makan = jumlah_porsi * 5000
    print(" Mie Goreng/Rebus",jumlah_porsi," Porsi : Rp.",total_makan)
    nama_makanan = (" Mie Goreng/Rebus")
elif menu_makanan == 4:
    total_makan = jumlah_porsi * 7000
    print(" Ketoprak",jumlah_porsi," Porsi : Rp.",total_makan)
    nama_makanan = (" Ketoprak")
elif menu_makanan == 5:
    total_makan = jumlah_porsi * 20000
    print(" Ikan Bakar",jumlah_porsi," Porsi : Rp.",total_makan)
    nama_makanan = (" Ikan bakar")
else:
    print(" Piihan Tidak Tersedia")

print()
print("|================================|")
print("|     : Pilih Menu Minuman :     |")
print("|================================|")
print("|1. Es Teh              Rp.4000  |")
print("|2. Es Jeruk            Rp.4000  |")
print("|3. Teh Botol Sosro     Rp.5000  |")
print("|4. Kopi Susu           Rp.5000  |")
print("|================================|")
menu_minuman = int(input(" Pilih Menu (1/2/3/4/5) : "))
jumlah_gelas = int(input(" Berapa Gelas : "))

if menu_minuman == 1:
    total_minum = jumlah_gelas * 4000
    print(" Es Teh",jumlah_gelas," Porsi : Rp.",total_minum)
    nama_minuman = (" Nasi Goreng")
elif menu_minuman == 2:
    total_minum = jumlah_gelas * 4000
    print(" Es Jeruk",jumlah_gelas," Porsi : Rp.",total_minum)
    nama_minuman = (" Es Jeruk")
elif menu_minuman == 3:
    total_minum = jumlah_gelas * 5000
    print(" Teh Botol Sosro",jumlah_gelas," Porsi : Rp.",total_minum)
    nama_mimunam = (" Teh Botol Sosro")
elif menu_minuman == 4:
    total_minum = jumlah_gelas * 5000
    print(" Kopi Susu",jumlah_gelas," Porsi : Rp.",total_minum)
    nama_minuman = (" Kopi Susu")
else:
    print(" Pilihan Tidak Tersedia")

# proses menghitung semua harga yang harus dibayar
makanan()
minuman()
jumlah_semuanya = total_makan + total_minum

# daftar pembelian
print()
print("|================================|")
print("|         Daftar Pembelian       |")
print("|================================|")
print("| Makanan :",nama_makanan,"\t |")
print("| Porsi   : ",jumlah_porsi,"\t\t\t |")
print("| Minuman :",nama_minuman,"\t |")
print("| Gelas   : ",jumlah_gelas,"\t\t\t |")
print("|================================|")
print("|    Jadi Yang Harus Di Bayar    |")
print("|================================|")
print("| Total :",jumlah_semuanya,"              |") 
print("|================================|")
print()
```
- ### Dibawah adalah gambaran ketika program dijalankan
