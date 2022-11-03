[Patika.dev](https://app.patika.dev/aybilemenko)


# Proje - 1 - Insertion Sort 

**22,27,16,2,18,6]**

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

- Big-O gösterimini yazınız.

- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.



-----

|  22  |  27  |  16  |  2   |  18  |  6   | 
| :--: | :--: | :--: | :--: | :--: | :--: |
|  22  |  27  |  16  |  2   |  18  |  6   |
|  22  |  16  |  27  |  2   |  18  |  6   |
|  16  |  22  |  27  |  2   |  18  |  6   |
|  2   |  16  |  22  |  27  |  18  |  6   |
|  2   |  6   |  16  |  22  |  27  |  18  |
|  2   |  6   |  16  |  18  |  22  |  27  |


-----
> Insertion sort time complexity : O(N²)  
> *18 sayısı "Average Case" kapsamına girer.



**[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**

|  7   |  3   |  5   |  8   |  2   |  9   |  4   |  15  |  6   |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  3   |  7   |  5   |  8   |  2   |  9   |  4   |  15  |  6   |
|  2   |  3   |  7   |  5   |  8   |  9   |  4   |  15  |  6   |
|  2   |  3   |  5   |  7   |  8   |  9   |  4   |  15  |  6   |
|  2   |  3   |  4   |  5   |  7   |  8   |  9   |  15  |  6   |
|  2   |  3   |  4   |  5   |  6   |  7   |  8   |  9   |  15  |



