# Binary Search Tree Project

### Soru
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

- Root'u dizinin en solundaki eleman olan 7 olarak seçelim.
- 7 sayısı en tepeye yazılır.
- Ardından gelen 5 sayısı 7'den küçük olduğu için 7'nin soluna yazılır.
- 1 sayısı 7den küçük olduğundan sol kol kontrol edilir. 1 sol tarafta yazılı olan 5 sayısından da küçük olduğu için 5'in soluna yazılır.
- 8 sayısı 7'den büyük olduğundan sağ tarafa yazılır.
- 3 sayısı 7'den küçük 5'ten küçük 1'den büyük olduğundan 1'in sağına yazılır.
- 6 sayısı 7'den küçük 5'ten büyük olduğundan 5'in sağına yazılır.
- 0 sayısı 7'den, 5'ten ve 1'den küçük olduğundan 1'in soluna yazılır.
- 9 sayısı 7'den ve 8'den büyük olduğu için 8'in sağına yazılır.
- 4 sayısı 7 ve 5'ten küçük, 1 ve 3'ten büyük olduğu için 3'ün sağına yazılır.
- 2 sayısı 7 ve 5'ten küçük, 1'den büyük, 3'ten küçük olduğu için 3'ün soluna yazılır ve sıralama oluşturulmuş olur.
```
            7
           / \
         5     8
       /  \    / \
      1    6      9
     / \
    0   3
       / \
      2   4
```
