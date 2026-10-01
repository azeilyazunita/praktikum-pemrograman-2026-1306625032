# Modul [02] - [Mencari Faktor Bilangan]

**Nama:** [Azeilya Junita]
**NIM:** [1306625032]  
**Kelas:** [Fisika C]  

---

## 1. Problem Statement
> Membuat program dengan menerima input sembarang bilangan bulat positif dari pengguna, kemudian mengidentifikasi semua pembagi bulat dari bilangan tersebut dan menampilkan semua hasik faktor dari bilangan tersebut

## 2. Mathematical Equation
> Bilangan = n
> n mod i = 0, untuk 1 ≤ i ≤ n

## 3. Algorithm
> 1. Mulai
> 2. Print "Program Faktor Bilangan"
> 3. Print "Nama : Azeilya Junita"
> 4. Print NIM  : 1306625032"
> 5. next = True
> 6. Definisikan fungsi faktorbilangan(n):
> 6.1 faktor = [ ]
> 6.2 Untuk i = 1 sampai n:
> 6.2.1 jika n mod i = 0, tambahkan i ke faktor
> 6.3 Kembalikan faktor
> 7. Selama next = True, ulangi:
> 7.1 Input bilangan, dengan prompt "Masukkan sembarang bilangan < 100 ( masukkan 0 untuk selesai )"
> 7.2 Jika bilangan = 0:
> 7.2.1 next = False
> 7.3 Jika bilangan ≠ 0 (selain itu):
> 7.3.1 hasil = faktorbilangan(bilangan)
> 7.3.2 Print "Bilangan", bilangan, "-> Faktornya =", hasil
> 8. Print "SELESAI"
> 9. Selesai
