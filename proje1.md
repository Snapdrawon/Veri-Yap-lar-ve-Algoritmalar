# **1. INSERTION SORT PROJESİ**

## **A.**

*[22,27,16,2,18,6] -> Insertion Sort*

*1.* *Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.*

*2.* *Big-O gösterimini yazınız.*

*3.* *Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.*

*4.* *Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.*

------

## **A-1)** ***Verilen dizinin insertion sort türüne göre aşamaları***

- Dizinin insertion sort türüne göre adımları:

```
1. [22,27,16,2,18,6]
2. [16,22,27,2,18,6]
3. [2,16,22,27,18,6]
4. [2,16,18,22,27,6]
5. [2,6,16,18,22,27]
```

## **A-2)** ***Big-O Gösterimi***

**Worst Case:** O(n^2)

**Average Case:** O(n^2)

**Best Case:** O(n)

## **A-3)** ***Time Complexity***

**Worst Case:**

```
[27,22,18,16,6,2]
```

**Average Case:**

```
[6,16,22,2,18,27]
```

**Best Case:**

```
[2,6,16,18,22,27]
```

## **A-4)** ***Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.***

Sıralamanın ortasında bulunduğu için **Average Case** kapsamına grirer.

------

## B.

## **[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**

```
1. [3,7,5,8,2,9,4,15,6]
2. [3,5,7,8,2,9,4,15,6]
3. [3,5,7,8,2,9,4,15,6]
4. [2,3,5,7,8,9,4,15,6]
```

### **[Patika.dev](https://app.patika.dev/) ekibine teşekkürler.**