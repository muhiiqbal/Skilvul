Soal 1
var i = 1 -> artinya index dimulai dari angka 1
i <= 100; -> yang berarti index sampai dengan kelipatan 100
i++ -> yang artinya index looping naik keatas
document.write -> berfungsi untuk menampilkan hasil di html

Soal 2
var nilaiAwal = 0; -> artinya nilai awal variabel tersebut 0
var i = 1 -> artinya index dimulai dari angka 1
i <= 100; -> yang berarti index sampai dengan kelipatan 100
i++ -> yang artinya index looping naik keatas
nilaiAwal += 2; -> artinya setiap looping ditambahkan dengan bilangan 2
console.log -> bergungsi untuk menampilkan output

Soal 3
var i = 0; -> artinya index dimulai dari angka 0
i <= 20; -> yang berarti index sampai dengan kelipatan 20
i++ -> yang artinya index looping naik keatas
i % 2 === 0 -> sisa bagi i dan 2 sama dengan 0

Soal 4
var jumlahKlik = 0; -> artinya nilai awal variabel tersebut 0
var konfirmasi = confirm("Apakah anda mau mengulang?"); -> variabel yang berfungsi untuk menampilkan confirm
jumlahKlik++; -> menampilkan jumlah klik

Soal 5
let answer = "1:13"; -> Jawaban yang benar
let guess = ""; -> Variabel yang digunakan untuk menyimpan jawaban dari user
while (guess !== answer) { -> Melakukan pengulangan selama jawaban masih salah
guess = prompt("Berapa konsumsi BBM dari Toyota "); -> Menampilkan prompt() dan menyimpan jawaban dari user ke variabel guess
if (guess === answer) { -> Memeriksa apakah jawaban dari user benar
alert("Selamat jawaban kamu benar!"); // Menampilkan jika jawaban benar
} else { -> Jika jawaban masih salah