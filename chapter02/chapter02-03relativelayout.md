# Membuat aplikasi dengan relative layout
- Selanjutnya untuk memahami relative layout kembalikan kode program pada activity_main.xml ke kondisi awal dan ubahlah *layout*-nya menjadi **relative layout**. Sehingga kode program dan tampilan berubah seperti gambar di bawah ini.
  
!['relativelayout'](img/02-relative-layout.png)

 > **RelativeLayout** adalah layout yang menempatkan suatu item relative terhadap parent atau item lain pada UI.

 - Untuk mencobanya tambahkan dua buah button pada layout anda bisa menambahkan dengan menggunakan pallet yang ada di sebelah kiri tampilan design kemudan jangan lupa menghapus TextView "hello world"

!['relativelayout'](img/02-relative-layout-button.png)
!['relativelayout'](img/02-relative-layout-button-drag.png)

- Ubahlah teks dan lebar dari button sehingga menjadi seperti gambar di bawah ini.

!['relativelayout'](img/02-relative-layout-button-width.png)

> untuk mengubah bisa menggunakan text mode atau pada design mode dengan mengklik button dan mengganti properties di kanan editor.

- Selanjutnya ubahlah tampilan dengan mengubah kode program melalui text mode sehingga seperti gambar di bawah ini.

!['relativelayout'](img/02-relative-layout-buttonpos.png)

Perhatikan pada kode program tersebut sebuah item di posisikan pada layout dengan memberikan detail posisinya relative terhadap parent. 

Pada *button* pertama ini mempunyai *properties*
- `android:layout_alignParentStart="true"`
- `android:layout_alignParentLeft="true"`
- `android:layout_alignParentTop="true"`

Dengan konfigurasi properties seperti di atas sebuah item akan diposisikan di sebelah kiri atas.

- untuk lebih memahami relative layout buatlah layout baru seperti pada gambar dibawah ini.

!['relativelayout'](img/02-relative-layout-button-baru.png)

- Berdasarkan percobaan di atas cobalah membuat layout yang sebelumnya menggunakan *linear layout* dengan *relative layout*.