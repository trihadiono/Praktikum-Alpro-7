# Praktikum-Alpro-7
STRING
#NAMA : Tri Hadiono
#NIM : 71200536
#Praktikum AlPro D
#UNIVERSITAS KRISTEN DUTA WACANA
#Referensi : modul dan ppt string

print("TOKO BUAH AAN")
buah=str(input("Jenis Buah: "))
inp=str(input("Masukkan kode penjualan: "))
a=inp.replace('a1','15000/kg')
b=a.replace('b1','8000/kg')
c=b.replace('c1','17000/kg')
d=c.replace('d1','12500/kg')
print(buah, ": Rp.", d)
