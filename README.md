# patikaDevDataStructures

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1 - İlk başlayacağımız sayı listenin başındaki sayı olduğundan dolayı 22'den başlarız ve sayımızın sağında kalan ifade ile karşılaştırız. Eğer karşılaştırdığımız sayı küçük ise ilk sayımızın ve diğer sayıların sol tarafına doğru sıralanmaya başlar.
2 - "|" işaretini kullanarak o ana kadar sıraladığımız sayıları gösterecektir.


### INSERTION SORT SIRALAMASI ###
Sayı Dizimiz = [22,27,16,2,18,6]

[22|, 27, 16, 2, 18, 6] 
[22, 27|, 16, 2, 18, 6]
[16, 22, 27|, 2, 18, 6] 
[2, 16, 22, 27|, 18, 6] 
[2, 16, 18, 22, 27|, 6] 
[2, 6, 16, 18, 22, 27]

### BIG-O GOSTERIMI ###

Best case    : O(n)
Average case : O(n^2)
Worst case   : O(n^2)


### TIME COMPLEXITY ###

Worst case: [27, 22, 18, 16, 6, 2]  
Best case: [2, 6, 16, 18, 22, 27]

### Answer 4 ###

Average case

### INSERTION SORT FIRST FOUR ###

[7| , 3, 5, 8, 2, 9, 4, 15, 6]
[3, 7| , 5, 8, 2, 9, 4, 15, 6]
[3, 5, 7| , 8, 2, 9, 4, 15, 6]
[3, 5, 7, 8| , 2, 9, 4, 15, 6]