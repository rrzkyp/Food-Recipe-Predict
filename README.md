Dataset yang diperlukan diimport ke dalam program dan membuat model KNN dengan euclidean distance sebanyak 3 neighbor

Lalu dari dokumen yang telah diimport, semua teksnya diubah menjadi vektor matriks untuk resep makanan

Kemudian diberikan fungsi untuk memprediksi energi makanan berdasarkan input. Jika makanan yang diinput terdapat pada dataset, maka akan mengeluarkan output energi yang sama pada dataset. Jika tidak ada di dalam dataset, maka input tersebut akan diubah menjadi vektor terlebih dahulu, mencari K tetangga terdekat dan diambil label energinya, kemudian rata-rata dari energi tersebut dihitung dan dikeluarkan menjadi output.

Lalu diberi program untuk menginput nama resep makanan yang ingin di cek jumlah energinya. Teks yang diinput harus diubah menjadi huruf kecil semua dan akan diprediksi jumlah energinya. Jika jumlah energi < 200, makanan tersebut dibolehkan untuk diet, energi di antara 200 dan 300 makanan diizinkan, dan jika energi > 300 maka makanan dilarang.

Pada hasil program, resep yang diinput terdapat dalam dataset yang dipakai sehingga akan mengeluarkan output yang sesuai pada dataset senilai 231, maka makanan tersebut diizinkan

Kemudian dicoba resep yang tidak terdapat dalam dataset yang dipakai sehingga akan memprediksi nilai energi makanan tersebut senilai 322.34, maka makanan tersebut dilarang




