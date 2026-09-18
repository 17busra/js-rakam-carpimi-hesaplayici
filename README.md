# JavaScript Rakam Çarpımı Hesaplayıcı ✖️

Bu proje, JavaScript kullanılarak matematiksel operatörler ve döngüler yardımıyla bir sayının basamaklarına nasıl ayrılacağını gösteren temel bir algoritma örneğidir.

**Projenin İşlevleri:**
* `prompt` komutu ile kullanıcıdan bir tam sayı girmesini ister.
* **Hata Kontrolü (Validation):** Kullanıcının sayı yerine harf veya kelime girmesi durumunda `isNaN` (Is Not a Number) fonksiyonu ile bunu tespit eder ve geçerli bir sayı girilene kadar uyarı vermeye devam eder.
* **Basamaklara Ayırma:** Geçerli bir sayı girildiğinde, `while` döngüsü ve Modulo (`%`) operatörü kullanılarak sayının her bir rakamı tek tek elde edilir.
* Rakamlar birbiriyle çarpılır ve yapılan matematiksel işlem (örneğin: `3*4*5 = 60`) `document.write` kullanılarak ekrana yazdırılır.

**Kullanılan Teknolojiler:**
* HTML
* Vanilla JavaScript (Saf JS)
