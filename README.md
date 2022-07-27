# Proje 1 (Insertion Sort)

## Soru -1

[22,27,16,2,18,6] -> Insertion Sort

**1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.**

*Cevap-1*

[2,27,16,22,18,6]

[2,6,16,22,18,27]

[2,6,16,18,22,27]

**2. Big-O gösterimini yazınız.**

*Cevap-2*

[22,27,16,2,18,6] n

[2,27,16,22,18,6] n-1

[2,6,16,22,18,27] n-2

[2,6,16,18,22,27] 1

n*(n+1)/2 = (n^2+n)/2 'den Big O(n^2) olmakta.

**3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.**

*Cevap-3*

Yaptığımız sıralamaya göre worst case O(n^2) olmaktadır.

**4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.**

*Cevap-4*

[2,6,16,18,22,27] -> son adımda 18 i sıralayabildiğimiz için **worst case** kapsamına girer.

## Soru-2

**[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**

*Cevap*

[2,3,5,8,7,9,4,15,6] (2 başa gitti 7 ile yer değişti)

[2,3,4,8,7,9,5,15,6] (3 zaten sıralıydı 4 ile 5 yer değişti)

[2,3,4,5,7,9,8,15,6] (5 ile 8 yer değişti)

[2,3,4,5,6,9,8,15,7] (5'ten sonraki en küçük 6 sıralandı ve 7 ile yer değiştirdi)

Insertion Sort'a göre ilk 4 adım yukarıdaki gibidir.


**https://www.patika.dev**

