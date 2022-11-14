# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

ROOT 7 dir,

1- dizinin ikinci elemanı olan 5, rootun solunda 1.düğümde bulunur.

2- dizinin üçüncü elemanı olan 1, rootun ve 5'in solunda 2.düğümde bulunur.

3- dizinin dördüncü elemanı olan 8, rootun sağında 1.düğümde bulunur.

4- dizinin beşinci elemanı olan 3, root ve 5 den küçük olduğundan ama 1 den büyük olduğundan 1 in sağına üçüncü düğüme yazılır.

5- dizinin altıncı elemanı olan 6, rootdan küçük 5 den büyük olduğundan 5'in sağına ikinci düğüm satırına yazıyoruz.

6- dizinin yedinci elemanı olan 0, rootdan 5 den ve 1 den küçük olduğundan 1'in soluna üçüncü düğüm satırına yazıyoruz.

7- dizinin sekizinci elemanı olan 9, rootdan ve 8 den büyük olduğundan 8'in sağına ikinci düğüm satırına yazıyoruz.

8- dizinin onuncu elemanı olan 4, rootdan ve 5 den küçük olduğundan 1 den ve 3 den büyük olduğundan 3'ün sağına dördüncü düğüm satırına yazıyoruz.

9- dizinin onbirinci elemanı olan 2, rootdan ve 5 den küçük olduğundan 1 den büyük olduğundan 3 den küçük olduğundan'3 ün soluna dördüncü düğüm satırına yazıyoruz.

                        7(ROOT)                       
                    /       \
                5               8                
            /       \               \
        1               6               9       
    /       \
0               3                                
            /       \
        2               4                      

