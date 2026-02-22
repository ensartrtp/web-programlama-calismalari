
#  Renk Eşleştirme Oyunu

Bu proje, kullanıcının aynı renkteki butonları ardarda seçerek eşleştirmeye çalıştığı, dikkat ve hafıza odaklı basit bir web oyunudur.

## 🕹️ Nasıl Oynanır?

* Ekrandaki renkli kutucuklara tıklayın.
* Eğer seçtiğiniz iki kutucuk **aynı renkteyse**, kutucuklar siyah renge dönerek eşleşme tamamlanır.
* Eğer renkler farklıysa seçim sıfırlanır ve yeni bir deneme yapmanız gerekir.

## 🛠️ Teknik Özellikler

* **CSS Grid:** Oyun alanı 4 sütunlu esnek bir ızgara yapısıyla oluşturulmuştur.
* **JavaScript Mantığı:** `querySelectorAll` ile butonlar dinlenmiş, `window.getComputedStyle` ile arka plan renkleri dinamik olarak karşılaştırılmıştır.
* **Hover Efekti:** Kullanıcı etkileşimini artırmak için butonlara üzerine gelindiğinde büyüme (`scale`) efekti eklenmiştir.
