# Selection-Sort-Projesi

[22,27,16,2,18,6] -> Insertion Sort örneği

1- [<22,27>,16,2,18,6]-> Doğru sırada
2- [22,<27,16>,2,18,6]-> 16 27'den küçük -> [22,16,27,2,18,6]-> [16,22,27,2,18,6]
3- [16,22,<27,2>,18,6] ->2 27'den küçük  ->[16,22,2,27,18,6]->[16,2,22,27,18,6]->[2,16,22,27,18,6]
4- [2,16,22,<27,18>,6] ->18 37'den küçük ->[2,16,22,18,27,6]->[2,16,18,22,27,6]
5- [2,16,18,22,<27,6>] ->6 27den küçük   ->[2,16,18,22,6,27]->[2,16,18,6,22,27]->[2,16,6,18,22,27]->[2,8,16,18,22,27]

Big-O = O(n^2)
18 sayısı Average Case durumunda olur.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1-[2,3,5,8,7,9,4,15,6]
2-[2,3,4,8,7,9,5,15,6]
3-[2,3,4,5,7,9,8,15,6]
4-[2,3,4,5,6,9,8,15,7]
