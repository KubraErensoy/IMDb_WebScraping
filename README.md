# Predicting Top 1000 Highest-Grossing Movies of All Time Using Regression

 Bir sinema filmi izlemek istersek nereden tavsiye alırız.İlk olarak arama motorunu kullanarak   aklımıza imdb sitesi gelir.İmdb sitesindeki bir film için oyuncular hakkında bilgi, filmler hakkında bilgi, yeni projeler, filmelere puan verme,filmleri yorum yapma gibi bilgileri bizlere sunar.
 
 Bu projede en yüksek hasılata sahip  1000 filmi web scraping yöntemi ile  https://www.imdb.com/ adresinden çekildi.Dataset 13 sütundan oluşur. 
 
 Bu projenin amacı çektiğimiz featureların göz önünde bulundurarak , toplam hasılatı tahmin edecek bir makine öğrenme modeli oluşturmaktır.
 
 ## Dataset

- movie_name:Filmin Adı
- release_year:Filmin vizyone girdiği yıl
- runtime: Filmin toplam süresi
- rating: Filme verilen oy sayısı
- genre: Filmin süresi
- metascore: Filmin kazandığı oy
- director: Yönetmen adı
- gross: Filmden kazaılan hasılat
- budget:Filme harcanılan bütçe
- critic_review:Eleştirmen yorumları
- user_review:Kullanıcı Yorumları

## Sonuç
- Linear Regression  algoritması en iyi sonuçu gösterdi
- Polynomial Regression, Ridge Regression, Lasso Regression  benzer sonuçlara sahip.

