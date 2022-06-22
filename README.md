# Veri-Yapilari-ve-Algoritmalar-Proje2

[16,21,11,8,12,22] -> Merge Sort
1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

<img width="414" alt="Merge sort" src="https://user-images.githubusercontent.com/75563269/175072947-1ce27860-9d7a-413e-8dba-76089957adec.png">


2. Big-O gösterimini yazınız.
Recursive bir fonksiyon olduğu için sürekli kendini çağırarak diziyi hep ikiye bölmektedir. 
Her bölünmüş dizinin Merge işlemi için de dizinin uzunluğu olan n işlem yapıldığından O(n*(logn)) --> O(6*(log6)) olacaktır.
