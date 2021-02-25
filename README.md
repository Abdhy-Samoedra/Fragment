# Pengertian Fragment
Fragment merupakan kombinasi sebuah layout XML dan kelas java yang mempunyai fungsi mirip dengan sebuah Activity tetapi memiliki lifecycle yang berbeda. Fragment merupakan komponen utuh yang memiliki view, event, dan logic selain itu
Fragment juga dapat dipakai berulang kali didalam activity 

# Kelebihan penggunaan Fragment
- Tidak perlu memasukkan nama file fragment ke dalam “AndroidManifest” yang diperlukan oleh activity.
- Fungsi yang berada pada activity dapat langsung digunakan dalam fragment tersebut tanpa harus membuat ulang. Contoh: pada saat back, fragment hanya perlu memanggil fungsi “getactivity

# Lifecycle Fragment
Fragment merupakan sebuah kelas yang mempunyai fungsi hampir sama dengan sebuah activity, dimana dalam sebuah fragment terdapat method method seperti onCreate(),  onStart(), onPause(), dan onStop(). lifeccycle dari fragment dan Activity mempunyai tahapan yang saling berhubungan, dimana  method method yang ada pada activity maupun Fragment akan saling terhubung
Berikut beberapa method yang ada pada lifecycle Fragment :
1. onAttach() = dipanggil saat sebuah fragment terhubung ke activity.
2. onCreate() = dipanggil saat sebuah fragment dibuat (objeknya di memori).
3. onCreateView() = dipanggil saat fragment sudah siap membaca sebuah layout.
4. onViewCreated() = dipanggil setelah onCreateView() dan memastikan layout yang dibaca fragment adalah non-null. Semua pengaturan view seperti pembacaan findViewById, menambah onClickListener dapat dilakukan di sini.
5. onActivityCreated() = dipanggil setelah activity pembaca sudah menyelesaikan onCreate()-nya.
6. onStart() = dipanggil setelah fragment siap untuk ditampilkan di layar.
7. onResume() = Dipakai untuk melakukan pembacaan data yang lebih “rumit” seperti lokasi, sensor, dll.
8. onPause() = Tempat melepas data “rumit”. Lakukan commit di sini.
9. onDestroyView() = dipanggil saat layout sebuah fragment akan dihapus dari memori, namun fragmentnya masih ada di memori.
10. onDestroy() = dipanggil jika fragment sudah tidak dipakai.
11. onDetach() = dipanggil saat fragment tidak lagi terhubung ke sebuah activity.

# First Fragment
![WhatsApp Image 2021-02-25 at 22 44 04 (4)](https://user-images.githubusercontent.com/54672937/109180905-f5206f80-77bd-11eb-8f89-856194aaa725.jpeg)

# Second Fragment
![WhatsApp Image 2021-02-25 at 22 44 04 (3)](https://user-images.githubusercontent.com/54672937/109180914-f6ea3300-77bd-11eb-8ee0-b935860552b2.jpeg)

