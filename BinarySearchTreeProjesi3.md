# Patika Veri Yapılar ve Algoritmalar Dersi Binary Search Tree Projesi



## **[7,5,1,8,3,6,0,9,4,2]** -> Binary-Search-Tree

* Bu dizinin binary search tree türüne göre aşamaları:

1. rakam=7, 7'nin Root olduğunu düşünüyoruz ve ilk sıraya Root Node olarak yerleştiriyoruz. 
1. rakam=5, 5 7'nin Child Node'u olarak aşağısına yazılacak ve 7'den daha küçük olduğu için solda yer alacak.
1. rakam=1,  Root=7'den başlayıp sorulur ve küçük olduğu için solunda yer alan Child Node=5'e sorulur ve ondan da küçük olduğu için 5'in Child Node'u olarak solunda yer alır.
1. rakam=8,  Root=7'den başlayıp sorulur ve büyük olduğu için 7'nin sağında Child Node olarak yer alır. 
1. rakam=3, Root=7'den başlayıp sorulur ve küçük olduğu için solunda yer alan Child Node=5'e sorulur ve ondan da küçük olduğu için 5'in Child Node'u=1'e sorulur ve ondan büyük olduğu için 1'in Child Nodu'u olarak sağında yer alır.
1. rakam=6, Root=7'den başlayıp sorulur ve küçük olduğu için solunda yer alan Child Node=5'e sorulur ve ondan büyük olduğu için 5'in Child Node'u olarak sağ tarafta yer alır.
1. rakam=0, Root=7'den başlayıp sorulur ve küçük olduğu için solunda yer alan Child Node=5'e sorulur ve ondan da küçük olduğu için 5'in Child Node'u=1'e sorulur ve ondan da küçük olduğu için 1'in Child Nodu'u olarak solunda yer alır.
1. rakam=9, Root=7'den başlayıp sorulur ve büyük olduğu için sağında yer alan Child Node=8'e sorulur ve ondan da büyük olduğu için 8'in Child Nodu'u olarak sağında yer alır.
1. rakam=4, Root=7'den başlayıp sorulur ve küçük olduğu için solunda yer alan Child Node=5'e sorulur ve ondan da küçük olduğu için 5'in Child Node'u=1'e sorulur, ondan büyük olduğu için 1'in Child Nodu'u 3'e sorulur, ondan büyük olduğu için 3'in Child Nodu'u olarak sağında yer alır.
1. rakam=2,  Root=7'den başlayıp sorulur ve küçük olduğu için solunda yer alan Child Node=5'e sorulur ve ondan da küçük olduğu için 5'in Child Node'u=1'e sorulur, ondan büyük olduğu için 1'in Child Nodu'u 3'e sorulur, ondan küçük olduğu için 3'in Child Nodu'u olarak solunda yer alır.

|      |      |      |      |      |      |      |      | 7    |      |      |      |      |      |      |      |      |      |      |
| ---- | ---- | :--: | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
|      |      |      |      |      | 5    |      |      |      |      | 8    |      |      |      |      |      |      |      |      |
|      |      |      | 1    |      |      |      | 6    |      |      |      | 9    |      |      |      |      |      |      |      |
|      |      |  0   |      | 3    |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
|      |      |      |      | 2    |      | 4    |      |      |      |      |      |      |      |      |      |      |      |      |

          7
         / \
        5   8
       / \   \
      1   6   9
     / \
    0   3
       / \
      2   4
