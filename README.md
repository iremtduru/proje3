# proje3
Binary-Search Tree
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
 
Root'u 7 olarak seçeriz.Sonrasında sayıları roota göre sıralama yaparız.
Sayılar roottan büyük ise rootun sağına,rootun soluna yazarak Binary Search Tree'yi oluştururuz.

Sırasıyla devam etmek gerekirse;
 5, 7nin solunda bulunur.
 1, 5 ve 7nin solunda bulunur.
 8, 7nin sağında bulunur.
 3, 5 ve 7nin solunda bulunur.
 6, 7nin solunda 5in sağında bulunur.
 0, 1 ve 7nin solunda bulunur.
 9, 7 ve 8in sağında bulunur.
 4 ve 2, 7nin solunda bulunur.

Binary Search Tree'yi şema olarak gösterdiğimizde ise;
                   
                                  7
                               /    \
                              5      8
                            /   \     \
                          1      6     9
                         /  \
                        0    3
                            /  \
                           2    4   
www.patikadev.com                           
