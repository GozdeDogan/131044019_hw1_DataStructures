# 131044019_hw1_DataStructures

Gebze Teknik Üniversitesi
2017 - Bahar Dönemi
Data Structures And Algorithms(CSE222)
HW1

-Object Oriented Programming gerekleri yerine getirildi.

Kullanılan dil: Java
Kullanılan IDE: İntellij IDEA Community 14.1.4
-Proje maven olarak açıldı.

Kullanılan Data Structures yapıları:
-ArrayList yapısı kullanıldı!


Requirements:
Simple Library Management System
Birden fazla personel(staff), birden fazla kullanıcı(user) var.
Sisteme kayıtlı olmayan biri sisteme giremez.
User kaydını sadece staff yapabilir.
Staff sisteme kitap ekleyip çıkartabilir.
User sistemden kitap ödünç alıp, ödünç alınan kitabı geri bırakabilir.
Bilgilerin tutulduğu bir .csv dosyası var.




DESIGN:
Dosya formatı:
u,ID,password
s,ID,password
b,name,writer,e
b,name.writer,notE

Kullanılan simgelerin anlamı:
u: user
s: staff
b: book
e: eligible(kitap sistemde yani ödünç almak için uygun)
notE: not eligible(kitap başka bir kullanıcı tarafından ödünç alınmış durumdaS)
