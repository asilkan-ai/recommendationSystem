# Recommendation System
Item-based collaborative filtering ile Recommendation System günümüzde oldukça sık kullanılmaktadır. Temel olarak sistemde, mevcut kullanıcılarının yaptığı değerlendirmeler baz alınarak yine kullanıcılara beğenebileceği ürünleri önermek vardır. Bu şekilde dizi-film önerisi veya bir e-ticaret sitesinde bir ürün önermek için kullanılabilir. Aşağıda buna ilişkin popüler bir medya hizmet sağlayıcısından alınan görüntü de bu sisteme örnektir. Görüldüğü üzere 'Because you watched Narcos' başlığı altında Narcos filmini izleyen kullanıcıya yine Narcos filmi ile ilişkili yapılar önerilmektedir.



 ![Screenshot_2](https://user-images.githubusercontent.com/73762823/154817921-688a1dea-f686-4024-8d18-f8a9e84d8312.png)


Bu örnekte ise IMDB veri setinden faydalanılarak bir filme benzer öneriler yapıldı. Veri setinde 10000 değerlemeye karşın tutarsız öneriler olmaması adına 100'ün üzerinde değerlendirmesi olan filmler öneri için dahil edildi. Örnek için seçilen film (Returns of the Jedi) ile ilgili çıktılar alındığında listede kendisinden hemen sonra gelen filmlerin aynı seride olması modelin doğruluğunu ortaya koyuyor.

![Screenshot_1](https://user-images.githubusercontent.com/73762823/154818349-9e80edbf-4918-420e-9662-27e149810798.png)
