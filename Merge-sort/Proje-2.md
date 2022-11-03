# Proje - 2 - Merge sort 

[Patika.dev](https://app.patika.dev/aybilemenko)

**[16,21,11,8,12,22]** -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız. - Cvp: **O (nlogn)** 

1. [16,21,11]  < ---------->  [8,12,22]
2. [16] | -  [21, 11] <----------> [8, 12] - |  [22]
3. [16] | - [21] - [11] <--------> [8] - [12] - | [22]
4. [16] | -  [11, 21] <---------> [8, 12] - | [22] 
5. [11, 16, 21] <----------> [8, 12 , 22]
6. [8,11,12,16,21,22]


Dizi ikiye ayrılır ve ayrılan her dizi kendi içlerinde tek başlarına kalana kadar ayrılmaya devam eder. 
Bölme işlemi bittikten sonra diziler sırayla karşılaştırılır ve birleştirme işlemi başlar. 
Bir bütün elde edene kadar birleştirme işlemi devam eder. 




