# Selection Sort Projesi

##[22,27,16,2,18,6] dizisinin Selection Sort'a göre aşamaları:

1.aşama 22 27 doğru (Doğru olduğu için değişmez)

2.aşama 27 16 yanlış(Yanlış olma durumunda doğru konuma gelen kadar sola kayar)
3.aşama 22-16-27
4.aşama 16-22-27

5.aşama 27-2 yanlış
6.aşama 16-22-2-27
7.aşama 16-2-22-27
8.aşama 2-16-22-27

9.aşama 27-18 yanlış
10.aşama 2-16-22-18-27
11.aşama 2-16-18-22-27

12.aşama 2-16-18-22-27-6 yanlış
13.aşama 2-16-18-22-6-27
14.aşama 2-16-18-6-22-27
15.aşama 2-16-6-18-22-27
16.aşama 2-6-16-18-22-274

Dizimizin son hali: [2, 6, 16, 18, 22, 27]

Dizi de yapılacak işlem eleman sayısını n diye belirtirsek her seferinde işlem yapacağımız sayı 1 azaldığı için n-1, n-2 şeklinde göstetiyoruz. 

Bu durumda selection sort türüne göre genel formülü n(n+1)/2 'ye göre dominant olanı almamız gerektiği için Big-O gösterimi = n²'dir.

18'e göre aramaya gerçekleştirirsek:
Time Complexity'ye göre Average Case'dir. Yani aradığımız sayının ortada kalma durumudur.

## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı


1.Aşama: 3,7,5,8,2,9,4,15,6

2.Aşama: 3,5,7,8,2,9,4,15,6

3.Aşama: 2,3,5,7,8,9,4,15,6

4.Aşama: 2,3,4,5,7,8,9,15,6


