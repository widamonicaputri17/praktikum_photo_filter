# WIDA MONICA PUTRI
# NIM 362358302008
# HASIL PRAKTIKUM :
![Screenshot 2024-11-04 112207](https://github.com/user-attachments/assets/4c680548-3b55-4d37-957b-40ce73e4ec52)
![Screenshot 2024-11-04 112321](https://github.com/user-attachments/assets/3a0dc803-c734-4ef7-b80d-cda25c77aa14)

# Jelaskan maksud void async pada praktikum 1
# Future<void>: 
yang menyatakan bahwa fungsi main akan menjalankan operasi yang bersifat tidak langsung
void menunjukkan bahwa fungsi ini tidak mengembalikan nilai apapun
# async: 
Kata kunci yang membuat fungsi main bisa menjalankan await di dalamnya, dan ini memungkinkan operasi berjalan secara tidak langsung atau tidak langsung selesai saat itu juga, sehingga kode setelah await tidak akan dieksekusi sampai operasi secara tidak langsung itu ditunggu dan selesai.

# Jelaskan fungsi dari anotasi @immutable dan @override
# Fungsi @immutable:
1. memastikan bahwa kelas tidak mengalami perubahan data, sehingga lebih aman dan mudah untuk diuji.
2. Menghindari bug yang mungkin terjadi akibat dari perubahan data yang tidak terduga.
3. Meningkatkan performa, karena data tidak berubah dan bisa dioptimalkan.
# Fungsi @override:
1. Memastikan bahwa metode di dalam subclass sesuai dengan metode di superclass yang ingin di-override.
2. Membantu pembaca kode untuk memahami bahwa metode tersebut menggantikan implementasi dari superclass.
3. Membantu mendeteksi kesalahan lebih awal, jika metode yang ingin di-override tidak ada di superclass.

