**[22,27,16,2,18,6]** 
Yukarı verilen dizinin Insertion Sort türüne göre aşamalarını yazınız.

    Insertion Sort, verilen diziyi sıralamak için kullanılan bir sıralama algoritmasıdır. Algoritma, dizinin ilk elemanını sıralanmış olarak kabul eder ve dizinin geri kalanını sıralanmış bölümle birleştirmek için kullanır.
    
        1.  Adım: [22, 27, 16, 2, 18, 6]
        2.  Adım: [22, 27, 16, 2, 18, 6]
        3.  Adım: [16, 22, 27, 2, 18, 6]
        4.  Adım: [2, 16, 22, 27, 18, 6]
        5.  Adım: [2, 16, 18, 22, 27, 6]
        6.  Adım: [2, 6, 16, 18, 22, 27]
    
    Son olarak dizi sıralanmıştır. [2,6,16,18,22,27]

**Big-O** gösterimini yazınız.


    Big-O = O(n)



Time Complexity: Dizi sıralandıktan sonra **18** sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

> 1.Average case: Aradığımız sayının ortada olması.
> 
> 2.Worst case: Aradığımız sayının sonda olması.
> 
> 3.Best case: Aradığımız sayının dizinin en başında olması.

    18 sayısı [2,6,16,18,22,27] dizisinin ortalarında bulunduğundan dolayı "Average case" kapsamına girer.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.


    Selection Sort, verilen diziyi sıralamak için kullanılan bir algoritmadır. Algoritma, dizinin ilk elemanını sıralanmış bölüm olarak kabul eder ve dizinin geri kalanını sıralanmış bölümle birleştirmek için kullanır. Aşağıda verilen [7,3,5,8,2,9,4,15,6] dizisi için Selection Sort algoritmasının ilk 4 adımı verilmiştir:
    
    1.  Adım: A[0]=2 . [2, 3, 5, 8, 7, 9, 4, 15, 6]
    2.  Adım: A[1]=3 . [2, 3, 5, 8, 7, 9, 4, 15, 6]
    3.  Adım: A[2]=4 . [2, 3, 4, 8, 7, 9, 5, 15, 6]
    4.  Adım: A[3]=5 . [2, 3, 4, 5, 7, 9, 8, 15, 6]