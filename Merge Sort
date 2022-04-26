# Merge Sort Projesi

## [16,21,11,8,12,22] 

**1. Merge sort aşamaları:**

1. Dizi `[16,21,11]` ve `[8,12,22]` olarak iki ayrı diziye ayrılır.
2. Birinci adımdaki ilk dizi de `[16,21]` ve `[11]` olarak ikiye ayrılır.
3. `[16,21]`  dizisi de `[16]` ve `[21]` olarak ikiye ayrılır. Daha fazla bölemeyeceğimiz için bu dizi sıralamaya hazır hale gelmiştir.
4. 16, 21'den küçük olduğundan bu iki dizi `[16,21]` şeklinde sıralanarak tekrar birleştirilir.
5.  İkinci adımda oluşturulan `[11]`  dizisi de daha fazla bölünemeyeceğinden sıralamaya hazırdır. 11, 16'dan küçük olduğundan `[16,21]` ve  `[11]` dizileri `[11,16,21]` olarak birleştirilir. Böylece 1.adımda oluşturulan iki diziden ilki kendi içinde sıralanmış oldu.
6. Birinci adımdaki ikinci dizi de `[8,12]` ve `[22]` olarak ikiye ayrılır.
7. `[8,12]`  dizisi de `[8]` ve `[12]` olarak ikiye ayrılır. Daha fazla bölemeyeceğimiz için bu dizi sıralamaya hazır hale gelmiştir.
8. 8, 12'den küçük olduğundan bu iki dizi `[8,12]` şeklinde sıralanarak tekrar birleştirilir.
9. Altıncı adımda oluşturulan `[22]` dizisi de daha fazla bölünemeyeceğinden sıralamaya hazırdır. 22, 12'den büyük olduğundan `[8,12]` ve  `[22]` dizileri `[8,12,22]` olarak birleştirilir. Böylece 1.adımda oluşturulan iki diziden ikincisi de kendi içinde sıralanmış oldu.
10. Oluşan  `[11,16,21]` ve `[8,12,22]` dizilerinin ilk terimleri birbirleri ile karşılaştırılır ve küçük olan değerler dizinin sırayla yerleştirilir.
- 11 ve 8 karşılaştırmasında 8 küçük olduğundan dizinin ilk terimi 8 olur.  `[8]`
- 11 ve 12 karşılaştırması sonucu dizinin ikinci terimi 11 olur. `[8, 11]`
- 16 ve 12 karşılaştırması sonucu dizinin üçüncü terimi 12 olur. `[8, 11, 12]`
- 16 ve 22 karşılaştırması sonucu dizinin dördüncü terimi 16 olur. `[8, 11, 12, 16]`
- 21 ve 22 karşılaştırması sonucu dizinin 5. terimi 21 olur. `[8, 11, 12, 16, 21]`
- Sona kalan 22 de dizinin sonuncu terimi olur.  `[8, 11, 12, 16, 21, 22]`
- 
**2. Big-O gösterimi:** O(n*log n)
