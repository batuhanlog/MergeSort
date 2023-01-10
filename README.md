# MergeSort
Patika.dev
Merge Sort, diziyi ikiye bölme ve sıralama sürecini tekrar birleştirme sürecini kullanarak diziyi sıralayan bir sıralama algoritmasıdır. Aşağıdaki adımları izler:

Dizi tek elemanlı parçalara ayrılır. Bu parçalar zaten sıralıdır.
İki yakın parça, sıralanmış bir parça oluşturmak için birleştirilir. Bu parçaların sağ ve sol tarafı karşılaştırılır ve küçük olan eleman dizinin başına yerleştirilir.
Adım 2 yukarıdaki dizinin tüm parçalarını birleştirene kadar tekrarlanır.
Merge Sort, worst case senaryosunda, dizinin en büyük elemanının en sonunda olduğu diziler için O(n * log(n)) olur. Average case senaryosu ve best case senaryosu aynıdır, her iki senaryo içinde de O(n * log(n)) olur.


[16],[21,11,8,12,22]
[11,16],[8,12,21,22]
[8,11,12,16],[21,22]
[8,11,12,16,21,22]
