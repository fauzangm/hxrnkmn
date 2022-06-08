# ----------------------------REVERSE ENGINEERING -----------------------

# Table Of Contents

- [Dynamic Analysis](#dynamic-analysis)
- [Disassembler](#disassembler)
- [Breakpoint](#breakpoint)
- [Register](#register)
- [StackView](#stack-view)
- [Tools Debugger yang digunakan](#tools-debugger-yang-digunakan)
- [Konsep Debugging IDA](#konsep-debugging-ida)
- [Toolbar Dynamic-analysis IDA](#toolbar-dynamic-analysis-ida)




## Dynamic Analysis

Dalam Dynamic analysis pengujian program dengan menganalisis dan mengeksekusi program secara real time atau memahami program dengan menjalankannya (Debugging)


## Disassembler
Disassembler hanya akan menampilkan kode dalam assembly dalam bentuk teks yang bisa dibaca manusia.


## Breakpoint
Breakpoint berfungsi untuk mempause program agar bisa menganalisis register / alamat memory dan melihat variabel

## Register
sebuah tempat untuk penampungan sementara  data-data yang akan diolah 
 


## Stack View
Tampilan isi dari stack program dan biasanya variabel local muncul di stack view



## Tools Debugger yang digunakan
- IDA pro


## Konsep Debugging IDA

Karena IDA merupakan aplikasi windows maka diperlukan remote debugging ke server local debugger linux dengan menggunakan port yang disediakan dan alamat hostname menggunakan localhost 127.0.0.1

## Toolbar Dynamic-analysis IDA
Yang paling penting di gunakan pada saat proses dynamic analysis 
- Continue	= melanjutkan program sampai selesai atau sampai terkena breakpoint
- Step Into	= menjalankan instruksi berikutnya dan jika ada pemanggilan fungsi akan masuk 		kedalamnya
- Step Over	= Menjalankan instruksi namun jika ada pemanggilan fungsi dia akan melewatinya
