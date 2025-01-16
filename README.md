# Patika-Dev--Insertion-Sort-Project
Patika Dev insertion Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Insertion Sort sıralaması:
1- Tüm indisleri tek tek kontrol edip minimum sayıyı bulur.
2- Min sayı=2 dizinin ilk indesiyle yani 22 ile değiştirilir. Son durum [2,27,16,22,18,6]
3- Dizinin 0. indesi sabit kalarak diğer indislerine bakılır ve en küçük olan bulunur. Ardından o sayı 1. indisle yer değiştirilir.
Son durum [2,6,16,22,18,27]
4- BU sefer dizinin 0 ve 1. indesi sabit kalıp diğer insiler için aynı işlem yapılır. Ta ki 5. indisise (n-1) kadar bu işlem devam eder.

Big-O gösterimi:
Adım 1 -> n
Adım 2 -> n-1
Adım 3 -> n-2
....
Adım n-1 -> 1
Toplam = (n*(n-1))/2 -> O(n^2)

Time Complexity: 
1- Average case: Aradığımız sayının ortada olması,
2- Worst case: Aradığımız sayının sonda olması, 
3- Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı Worst Case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
1- min=2 -> 7 ve 2'yi değiştir -> [2, | 3, 5, 8, 7, 9, 4, 15, 6]
2- min=3 -> Değişikliğe gerek yok -> [2, 3, | 5, 8, 7, 9, 4, 15, 6]
3- min=4 -> 5 ve 4'ü değiştir -> [2, 3, 4, | 8, 7, 9, 5, 15, 6]
4- min=5 -> 8 ve 5'i değiştir -> [2, 3, 4, 5, | 7, 9, 8, 15, 6]


