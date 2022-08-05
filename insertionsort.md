## 1. Soru: Aşağıda verilen dizinin sort türüne göre aşamalarını yazınız.
### [22,27,16,2,18,6] -> Insertion Sort
1. Adım: [2,27,16,22,18,6] #Sıradaki en küçüğü bulup başa getiriyoruz.
2. Adım: [2,6,16,22,18,27] #1. en küçük olduğunu bilediğimizden 1. ile işimiz bitti. 1. dışındaki diğer datalar arasındaki en küçüğü bulup başa getiriyoruz.
3. Adım: [2,6,16,22,18,27] #1. ve 2. yerleşti. Diğer 4 datadan en küçük olanı bulup en başa koyuyoruz. Bu 4'ü arasından en küçük en başta olduğu için işlem yapmıyoruz.
4. Adım: [2,6,16,18,22,27] #1.,2. ve 3. yerleşti. Diğer 3 datanın en küçük olanını en başa koyuyoruz.
5. Adım: [2,6,16,18,22,27] #1.,2.,3. ve 4. yerleşti. Diğer 2 dataya bakıyoruz. 2 data arasındaki en küçük başta olduğu için işlem yapmıyoruz.

## 2. Soru: Big-O gösterimini yazınız.
n tane elemanımız var. Insertion sort'un time complexitysi O(n^2)'dir. n=6 olduğu için O(62)=36 olacaktır.

## 4. Soru: Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
18 sayısı average case kapsamına girer.

## 5. Soru: [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1. Adım: [2,3,5,8,7,9,4,15,6]
2. Adım: [2,3,5,8,7,9,4,15,6]
3. Adım: [2,3,4,7,8,9,5,15,6]
4. Adım: [2,3,4,5,8,9,7,15,6]
5. Adım: [2,3,4,5,6,9,7,15,8]

