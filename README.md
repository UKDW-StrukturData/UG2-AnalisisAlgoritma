# UG2-AnalisisAlgoritma

Lakukan perbandingan kinerja dari fungsi iteratif dan fungsi rekursif untuk mendapatkan suku ke-n dari suatu Deret Ajaib. Perbandingan dilakukan dengan mencatat waktu yang diperlukan untuk mendapatkan suku Ajaib ke-1 sampai ke-50(nilai n) dengan kedua fungsi tersebut. Kemudian berdasarkan catatan waktu tersebut, buatlah tabel catatan waktu terhadap n.

Anda harus menghasilkan:
1. Source code fungsi Deret Ajaib ke-n secara iteratif dan rekursif
2. Tabel catatan waktu dari kedua fungsi tersebut, dengan nilai n= 1 sampai 50

KETERANGAN:
Deret ajaib ke-n maksudnya adalah suku ke-n dari deret bilangan yang 3 angka pertamanya sudah di tentukan yaitu 1,3,5 dan suku ke-4 dihitung dari suku ke-(n-2)*suku ke-(n/2) dengan pembulatan ke atas.
U1 = 1
U2 = 3
U3 = 5
U4 = U(n-2) * bulatkan((n : 2))

Misal: suku ke-4 dihitung dari suku ke-(n/2) yaitu 3 dikali dengan suku ke-(n/2) yaitu 2, maka suku ke-4 adalah 3*2 = 6. Kemudian suku ke-5 dihitung dari n-2 yaitu 5 dikali dengan 5/2 yaitu 3. Maka suku ke-7 adalah 5*3 = 15
