## D-503 Game Web Site with Sass

Sass yaklaşımlarına aşinalık ve sass teknolojisini anlama.

#### Proje Amacı

Bu projede sass konularına daha iyi hakim olabilmek için farklı örnekleri de görebilme adına hazırlanmış bir web sitedir.

- Teknoloji yapısını iyi anlamak
- Kullanılan yapılara aşina olmak
- Sass folder structure ile çalışma mantığını anlamak
- @import, @extend, @include @mixin ile çalışmak
- Componentlerle çalışma

#### Kullanılanlar

- Hover visited active focus hareketleri ile çalışma
- Değişkenlerle çalışma ve utilites class yapıları ile çalışma
- Mixins kullanarak kod tekrarlarından kurtulma
- Sass ile animasyonlarla çalışma
- Sass ve kütüphanelerin iç içe kullanımı
- Responsive uyumlu tasarım

## Kurulum

Projenin kurulumu için aşağıdaki adımları izleyin:

1. Proje dosyalarını bilgisayarınıza indirin veya klonlayın.
2. Terminali açın ve proje dizinine gidin: `cd proje-klasoru`.
3. Gerekli bağımlılıkları yüklemek için `npm install` komutunu çalıştırın.
4. Projeyi çalıştırmak için `npm start` komutunu kullanın.
5. Tarayıcınızda `http://localhost:3000` adresine gidin ve projeyi görüntüleyin.

## Kullanım

Proje kullanımıyla ilgili aşağıdaki detayları göz önünde bulundurun:

- Proje ana sayfasında mevcut olan örnekleri inceleyebilirsiniz.
- Proje dosyalarına yeni componentler yerleştirmek için kullanın:  `_components.scss`
- Proje yapısını ve kullandığınız Sass tekniklerini inceleyerek çalışma mantığını anlayabilirsiniz.
- Proje dosyalarında `_abstracts.scss` ile daha gelişmiş yapılar ekleyin.

```SCSS
>> _abstracts.scss

//Örnek Yapı Ekleme

.primaryButton{
    $-dark {
        background-color:red;
    }
    $-white {
        background-color:white;
    }
}
```

## Katkıda Bulunma

Eğer projeye katkıda bulunmak isterseniz, lütfen aşağıdaki adımları takip edin:

1. Bu projeyi fork edin.
2. Yeni bir dal oluşturun: `git checkout -b feature/yeni-ozellik`.
3. Yaptığınız değişiklikleri işleyin: `git commit -am 'Yeni özellik ekle'`.
4. Dalınıza itme yapın: `git push origin feature/yeni-ozellik`.
5. Pull Request göndermek için GitHub üzerinden talep oluşturun.

## İletişim

Herhangi bir sorunuz, öneriniz veya geri bildiriminiz varsa, lütfen göndermekten çekinmeyin.:relieved:

Daha fazla bilgi için [proje dokümantasyonunu](https://github.com/ad0pa/firstsassproject) ziyaret edin.

Teşekkür ederiz!
