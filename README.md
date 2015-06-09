# Belajar Rails

[![Join the chat at https://gitter.im/rezajatnika/belajar_rails](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/rezajatnika/belajar_rails?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

> This work is licensed under the Creative Commons Attribution-ShareAlike 4.0
  International License. To view a copy of this license, visit
  http://creativecommons.org/licenses/by-sa/4.0/


## Pendahuluan

Selamat datang di buku **Belajar Rails**. Pada buku ini kamu akan mempelajari
bagaimana framework Ruby on Rails bekerja dan bagaimana membuat aplikasi web
menggunakan Ruby on Rails.

Buku ini tidak akan membuat kamu menjadi Rails master dan siap untuk industri
aplikasi web. Untuk dapat sampai pada level tersebut diperlukan berbulan-bulan
bahkan bertaun-taun belajar dan berlatih. Langkah kamu dapat dimulai dengan
membaca buku ini.

Pada akhir buku ini kamu akan memiliki aplikasi web berupa blog dan bagaimana
membuatnya *online* supaya dapat diakses melalui internet.

![Blog](http://tutorial.djangogirls.org/en/images/application.png)

Apabila dalam pengerjaan tutorial pada buku kamu mengalami kesulitan, langsung
saja tanyakan di *chat room*. Tautan untuk bergabung ada pada awal isi buku.


## Prasyarat

Sebenarnya tidak ada prasyarat (*prerequisites*) khusus untuk memulai tutorial
pada buku ini, namun sangat disarankan kamu memiliki dasar-dasar pemrograman
dan akrab dengan lingkungan *operating system* berbasis
[Unix](http://en.wikipedia.org/wiki/Unix) atau
[Unix-like](http://en.wikipedia.org/wiki/Unix-like).

Seperti namanya, Ruby on Rails, framework ini dikembangkan dengan bahasa
pemrograman Ruby dan merupakan framework untuk aplikasi web. Sehingga diperlukan
sedikit pemahaman tentang HTML, CSS, JavaScript, dan Ruby sendiri.

Apabila kamu belum pernah mengetahui tentang HTML, CSS, dan JavaScript, Saya
merekomendasikan untuk membaca
[Mozilla MDN](https://developer.mozilla.org/en-US/Learn/HTML) sebelum memulai
tutorial ini, dan apabila belum akrab dengan Ruby, kamu bisa mencoba Ruby
langsung pada web browser di [Try Ruby](http://tryruby.org/). Buku teks
[Well Grounded Rubyist](http://www.manning.com/black2/) merupakan salah satu
buku yang direkomendasikan untuk belajar Ruby.


## Konvensi pada Buku

Konvensi pada buku ini dapat dijelaskan sendiri dengan melihat format
penulisannya. Tutorial pada buku ini banyak menggunakan *command line*, setiap
perintah *command line* selalu diawali dengan simbol dolar ($).

     $ echo 'Hello, world!'

Contoh source code pada buku ini:

```ruby
class User
  attr_accessor :first_name, :last_name

  def full_name
    [@first_name, @last_name].join(' ')
  end
end
```

## Tentang

Buku ini ditulis oleh [Reza Jatnika](mailto:rezajatnika@gmail.com) menggunakan
[GitBook](https://www.gitbook.com/). Apabila kamu menemukan kesalahan pada isi
penulisan buku ini, jangan segan untuk membuat *issue* baru di
[sini](https://github.com/rezajatnika/belajar_rails/issues).
