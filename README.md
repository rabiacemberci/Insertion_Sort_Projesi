# Insertion Sort Projesi  
[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.  
[22|,27,16,2,18,6]  
[22,27|,16,2,18,6]  
[22,16,27|,2,18,6]-->[16,22,27|,2,18,6]  
[16,22,2,27|,18,6]-->[16,2,22,27|,18,6]-->[2,16,22,27|,18,6]  
[2,16,22,18,27|,6]-->[2,16,18,22,27|,6]  
[2,16,18,22,6,27|]-->[2,16,18,6,22,27|]-->[2,16,6,18,22,27|]-->[2,6,16,18,22,27]  

2.Big-O gösterimini yazınız.  
O(N^2)

3.Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.  
 
Worst case:   
Eğer küçükten büyüğe sıralanmasını istediğimiz dizide tam tersi bir senaryo varsa. Her sayı için en sondaki sayı başa gelene kadar kaydırılacak. n değerine gidene kadar tüm sayıların toplamı kadar üzerinden geçilecek. Sayıların toplamı (n*n+1)/2 dir. Bu durumda Worst Case: O(n^2)  

Best case:  
En iyi durumda büyükten küçüğe yada küçükten büyüğe sıralı bir dizi verilir. Her hangi bir sayı yer değiştirmeyecek. Sıralama çubuğumuz n tane değer kadar kayacak. Bu durumda Best Case: O(n)  

Average case:  
Average case'de ise Best case ve Worst case'in ortalamasıdır. Yani O(n^2) dir.  

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.  
Dizi sıralandıktan sonra -->[2,6,16,18,22,27] 18 değerinin dizinin ortasında olduğunu görüyoruz. Bu yüzde
ne BEST case nede WORST case değildir. Bize ortalama bir değer verir. AVERAGE CASE  

-----  
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[7|,3,5,8,2,9,4,15,6]  
[3,7|,5,8,2,9,4,15,6]  
[3,5,7|,8,2,9,4,15,6]  
[3,5,7,8|,2,9,4,15,6]  






