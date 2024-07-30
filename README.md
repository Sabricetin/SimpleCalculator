## Basit Hesap Makinesi Uygulaması (SimpleCalculator)

Bu Swift kodu, basit bir hesap makinesi uygulamasını oluşturur. Uygulama, kullanıcıların iki sayı arasında toplama, çıkarma, çarpma ve bölme işlemlerini yapmalarını sağlar. Her bir buton tıklaması, ilgili matematiksel işlemi gerçekleştirir ve sonucu ekranda gösterir.

### Özellikler

- **Arayüz Elemanları:**
  - `firstText`: İlk sayıyı girmek için kullanılan metin alanı.
  - `secondText`: İkinci sayıyı girmek için kullanılan metin alanı.
  - `resultLabel`: Hesaplama sonucunun gösterildiği etiket.

### İşlevler

- `viewDidLoad()`: Görünüm yüklendiğinde çağrılır. Başlangıç ayarlarını yapar.
- `sumClicked(_:)`: Toplama butonuna tıklanıldığında çağrılır. Girilen iki sayıyı toplar ve sonucu gösterir.
- `minusClicked(_:)`: Çıkarma butonuna tıklanıldığında çağrılır. Girilen iki sayıyı çıkarır ve sonucu gösterir.
- `multiplyClicked(_:)`: Çarpma butonuna tıklanıldığında çağrılır. Girilen iki sayıyı çarpar ve sonucu gösterir.
- `divideClicked(_:)`: Bölme butonuna tıklanıldığında çağrılır. Girilen iki sayıyı böler ve sonucu gösterir.

### Kodun Genel Yapısı

- **Sonuç Değişkeni:** `result` adında bir değişken, hesaplama sonucunu tutar.
- **Arayüz Elemanları:** Kullanıcıdan giriş almak ve sonuçları göstermek için `UITextField` ve `UILabel` bileşenleri kullanılır.
- **Buton Tıklama İşlevleri:** Her bir matematiksel işlem için ayrı ayrı buton tıklama işlevleri tanımlanmıştır. Kullanıcının girdiği değerler `Int` olarak dönüştürülür ve ilgili matematiksel işlem gerçekleştirilir. Sonuç `resultLabel` etiketi aracılığıyla gösterilir.
