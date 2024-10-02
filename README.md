# HaxBall Online - Gelişmiş v1 Bot
Geçmiş dönemlerde HaxBall Online YouTube kanalında paylaşılmış olan v1 bot 2024 şartlarına göre revize edilmiş olup ekstra özellikler eklenmiştir.

Başlıca özellikler:

* Son oyuncu slotu yetkililere ait, normal kullanıcılar kicklenir.
* '!kayıt ŞİFRE ŞİFRE' şeklinde kayıt sistemi. Şifreler minimum 5 karaktere sahip olmalı. */*Şifreler Cryptr kullanılarak veri tabanına şifrelenerek işlenir.*\* Bu sayede kullanıcı ve yönetici gizliliği sağlanır.
* Kayıt olmuş kullanıcıların auth ve conn değerleri veri tabanında saklanır.
* '!giriş ŞİFRE' şeklinde giriş sistemi. Aynı bilgisayardan tekrar tekrar odaya katılma durumunda oto giriş sistemi sayesinde tekrar şifre istenmez.
* Giriş yapmamış kullanıcılar(Kaydı olup) sohbeti kullanamaz ve 20 saniye içerisinde giriş yapmazsa otomatik kicklenir.
* Kayıt olmuş kullanıcılar için istatistik(Kazanma, kaybetme, gol, k.k, cs) veri tabanına işlenir.
* Admin olarak atanmış kullanıcılar giriş yaptıklarında otomatik olarak yetkisi verilir.
* Yavaşlatılmış chat modu(5 saniyelik zaman aşımı) 
`* Yöneticiler için '!şifredeğiştir' komutu eklendi. Şifresini unutmuş kullanıcılara yöneticiler yardımcı olabilir.(Belirlenen yeni şifre aynı şekilde cryptr kullanılarak şifrelenip veri tabanına kaydedilir)
* Kullanıcılar için 100(Ayarlanabilir) karakter limiti belirlendi.
* Link filtresi eklendi.
* Küfür filtresi eklendi.
* Stadyumu artık oyun içinden değil, kodlardan dilediğiniz gibi değişip custom stadyum ekleyebilirsiniz.
* Kullanıcı mesajları(Tabii şifre v.s komut kullanımları hariç) Discord'a webhook vasıtası ile gönderiliyor.
* Maç kayıtları webhook vasıtası ile Discord'a gönderiliyor.
* Otomatik olarak 5 dakikada bir (Ayarlanabilir) veri tabanında yer alan duyuruları sırasıyla odalara gönderir. Kod değişikliği yapmadan, odaları aç-kapat yapmadan duyurularınızı güncelleyebilirsiniz.
* Kara liste eklendi. Veri tabanına eklediğiniz isim, auth ve conn(Ne yazık ki HaxBall'ın el verdiği kadar :/) değerlerinden herhangi birine takılan kullanıcı otomatik olarak yasaklanır. Kodda değişiklik yapmadan, odaları aç-kapat yapmadan dilediğiniz gibi veri tabanında güncelleme yapıp yeni yasaklama oluşturabilirsiniz.

Tüm bunların hepsi tamamen ücretsiz olarak HaxBall Online YouTube kanalında paylaşılmış olup ücretli satılması, paylaşılması yasaktır.

HaxBall Online YouTube - https://www.youtube.com/@haxballonline

HaxBall Online Discord - https://www.discord.gg/qsHq2ZP

Dip Not: Revizasyon çalışmalarında mertushka ve jakjus tarafından geliştirilmiş olan haxball.js kütüphanesi kullanılmıştır.

Haxball.js GitHub - https://github.com/mertushka/haxball.js
