# VY_KS_2_2_PROJECT
Bu algoritma da(silhouette coefficient), belirli bir veri kümesindeki noktaları iki kümeye ayırır. İlk adımda, rastgele iki nokta seçilir ve her nokta bir kümeye atanır. Sonra her nokta en yakın kümeye atanır ve kümelerin merkezleri yeniden işlenir. Bu işlem belirli bir sayıda tekrarlanır(verdiğim örnekte x10 defa) ve sonunda iki kümeye ait son konumlar çıkartılır.

Kısaca Kodun genel işleyişi, iki fonksiyon kullanarak gerçekleştirilir. İlk fonksiyona(a(i)) her noktanın hangi kümeye ait olduğunu belirler. İkinci fonksiyon(b(i)) kümelerin merkezlerini yeniden hesaplar ve son konumu bulur.
