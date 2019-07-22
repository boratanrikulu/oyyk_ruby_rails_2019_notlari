* Ruby ----> default yorumlayıcısı Matz tarafından yazılan MRI yorumlayıcısıdır.
* Rails Toolbox

---

## bundler

https://bundler.io/

Bundler ile bir ruby projesinde gem'leri kolayca yönetebiliriz.

```sh
mkdir bundler_test
cd bundler_test
bundle init
```

yaptığımızda Gemfile yaratacak.

DSL - Domain Specific Language

Bundler, bir dünya gem olması, ve bir projede bir çok gem kullandıldığından otomatik olarak herşeyi kurmak içindir. (örneğin projemizde prawn var, gem install prawn yapmak yerine gemfile'e yazarız ve bundler ile kurulumu yaparız.)

---

## rbenv

Rbenv ile kurabileceğimiz ruby versiyonlarına aşağıdaki gibi bakabiliriz.
```sh
rbenv install --list
```

rbenv update'lemek için
```sh
cd /home/fsutil/.rbenv/plugins/ruby-build && git pull && cd -
```

version kurmak için
```sh
rbenv install 2.7.0-preview1
```

global ruby version setlemek için
```sh
rbenv global 2.7.0-preview1
```

bi projeye özel set'lemek için
```sh
rbenv local 2.5.3
```

---

## rack

gemfile'e
```ruby
gem 'rack', '~> 2.0.1'
```

```sh
bundle install
```

* Sistemde hali hazırda var ise using, yok ise installing der.

---

## bundle

require,

git,
```ruby
gem 'nokogiri', :git => '', :branch => '1.4'
```

Gemfile'da ruby versiyonu belirtebiliriz. İlgili versiyon kullanılmıyorsa hata verecektir.

* ">=" ise eşit veya büyük olabilir ama asla majorü kapsamaz.
* ""
ODEV

---

## Hyper Text Transfer Protocol
## Hyper Text Markup Language

https://www.w3.org/  
https://www.w3schools.com/
https://webkit.org/