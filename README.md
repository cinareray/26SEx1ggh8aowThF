# 26SEx1ggh8aowThF

* Veri setindeki değişkenlerin ısı haritasına bakıldı ancak %70 üzeri bağımlı değişken görülmediği için indirgenme yapılmadı.
* Veriler One-Hat döüşümü uygulanarak çok kategorili değişkenlerin standartdizasyon işlemi gerçekleştirildi.
* Veriler 0-1 arasında bir normalisazyon işlemne tabi tutuldu.
* Aykırı olan gözlemlerin giderilmesi için aşağı baskılama yöntemi(Downsampling) ve LOCAL OUTLİER FACTOR kütüphanesi kullanıldı. Komşu yoğunluğu 20, yoğunluk ise 0.1 olarak  seçildi.
* KNeighbors ML algoritması kullanıldı. 'n_neighbors' parametresi Grid_Searcg_CV kütüphanesi kullanılarak bulundu.
* Modelin doğruluk oranı %92 olarak bulundu.
* Hata ortalama kareler toplamı(MSE) = 0.072, Hata ortalama kareler toplamının karekökü(RMSE) = 0.269 hataları bulundu.
* Model farklı  veri setleri ile test edilerek performansına bakıldı.Ortalama Doğruluk Performansı =%92, Doğruluk Skoru Standart Sapması = %0.13 olarak bulundu.
