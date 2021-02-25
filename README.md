# Pengertian Fragment
Fragment merupakan kombinasi sebuah layout XML dan kelas java yang mempunyai fungsi mirip dengan sebuah Activity tetapi memiliki lifecycle yang berbeda. Fragment merupakan komponen utuh yang memiliki view, event, dan logic selain itu
Fragment juga dapat dipakai berulang kali didalam activity 

# Kelebihan penggunaan Fragment
- Tidak perlu memasukkan nama file fragment ke dalam “AndroidManifest” yang diperlukan oleh activity.
- Fungsi yang berada pada activity dapat langsung digunakan dalam fragment tersebut tanpa harus membuat ulang. Contoh: pada saat back, fragment hanya perlu memanggil fungsi “getactivity

# Lifecycle Fragment
Fragment merupakan sebuah kelas yang mempunyai fungsi hampir sama dengan sebuah activity, dimana dalam sebuah fragment terdapat method method seperti onCreate(),  onStart(), onPause(), dan onStop(). lifeccycle dari fragment dan Activity mempunyai tahapan yang saling berhubungan, dimana  method method yang ada pada activity maupun Fragment akan saling terhubung

