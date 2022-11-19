
## Selection Sort Project

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarıda verilen Dizinin sort türüne göre aşamalarını yazınız
- [2,27,16,22,18,6] ..............(n)
- [2,6,16,22,18,27] ............ (n-1)
- [2,6,16,22,18,27] .............(n-2) Değişiklik Yok
- [2,6,16,18,22,27] .............(n-3)
- [2,6,16,18,22,27] .............(n-4) Değişiklik Yok
- [2,6,16,18,22,27] ..............(1)

2. BigO Gösterimini Yapınız.

- (n*(n-1))/2  ==>  (n^2+n)/2  ==> n^2 Dominant ==> BigO = O(n^2)

3. Time Complexity: Dizi sıralandıktan sonra 18 Sayısı aşağıdaki caselerden hangisinin kapsamına girer yazınız.

- Average Case: Aradığımız Sayının Ortada Olaması.
- Worst Case:   Aradığımız Sayının Sonda Olması.
- Best Case:    Aradığımız Sayının En Başta Olması.
- **[2,6,16,18,22,27] Sıralandığında 18 ortada kaldığı için Average Case**
