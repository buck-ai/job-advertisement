# En Kısa Yol Algoritması
![Harita](/images/harita.jpg)
Yukarıda ki haritada yer alan **Memphis** ile **Savannah** arasında ki en kısa yolu bulan kaç şehirden geçtiğini ve toplam yolun maliyetini hesaplayan ruby kodunu yazınız.

# Aktif Cihazlar
Aşağıda ki kriterlere uyan basit bir rails uygulaması yazmanızı ve bunu github üzerinde herkese açık olarak bizle paylaşmanızı bekliyoruz;
1. Sisteme kullanıcı veya cihaz olarak giriş yapılmalı.
2. Sisteme kullanıcı kendisi kayıt olabilmeli.
3. Sisteme kullanıcı giriş yaparak cihaz adı ile birlikte cihaz ekleyebilmeli.
4. Sisteme cihaz eklendikten sonra cihaza ait benzersiz bir kimlik numarası(6 karakter aralığında büyük harf, küçük harf ve sayı içerebilir) ve parola üretilmelidir(8-12 karakter aralığında büyük harf, küçük harf ve sayı içerebilir. Geri dönüşü olmayan bir algoritma ile şifrelenmeli). Üretilen bu bilgiler kullanıcıya bir defaya mahsus gösterilmelidir.
5. Sisteme cihaz olarak giriş yapmak istendiğinde cihaza ait kimlik numarası ve parola girilmelidir. Cihaz olarak giriş yapıldığında cihazın sisteme bağlı olduğu anlık olarak takip edilebilmelidir(Veri tabanında is_active adında bir boolean kolon üzerinden).