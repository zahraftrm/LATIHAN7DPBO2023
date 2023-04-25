# LATIHAN7DPBO2023

Saya Zahra Fitria Maharani NIM 2102545 mengerjakan soal Latihan 7 dalam mata kuliah Desain dan Pemrograman Berbasis Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## DESAIN PROGRAM

Merubah dan menambah syntax pada program agar :
1. Ketika user memindahkan bola ke atas/bawah/kanan/kiri, maka nilai dari score akan selalu bertambah satu. 
Perubahan syntax tersebut dilakukan di file Controller.java dengan menambahkan variabel global score dan merubah syntax pada method keyPressed menjadi game.setScore(score+=1); . 
2. Ketika user memindahkan bola ke atas misalnya kemudian memindahkannya ke atas lagi, maka nilai score tidak bertambah (begitu pula dengan arah bawah/kiri/kanan).
Perubahan syntax tersebut dilakukan di file Controller.java dengan menambahkan variabel global keyBefore dan menambah syntax pada method keyPressed untuk menampung nilai key sebelumnya, yaitu keyPressed = key; . 

## DOKUMENTASI PROGRAM

<img src="https://github.com/zahraftrm/LATIHAN7DPBO2023/blob/main/Dokumentasi%20Program.gif" width=85% height=85%>
