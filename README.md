Proje 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.


Cevap:

Dizinin en başındaki eleman root olarak seçilir. Yani 7.

    5 elemanı, 7'den küçük olduğu için 7'nin soluna gelir.
    1 elemanı, 7'den küçük olduğu için 7'nin soluna gelir. Daha sonra 5 elemanından küçük olduğu için yeni bir bağ ile sol tarafa yerleştirilir.
    8 elemanı, 7'den büyük olduğu için 7'nin sağına geçer.
    3 elemanı, 7'den küçük olduğu için sola, 5 elemanından küçük olduğu için sola, 1'den ise büyük olduğu yeni bir bağ ile sağa gelir.
    6 elemanı, 7'den küçük olduğu sola, 5'den büyük olduğu için yeni bir bağ ile sağ tarafa geçer.
    0 elemanı, 7'den küçük olduğu için sola, sırasıyla 1'e kadar gelir. 1'den küçük olduğu için sol tarafa yerleştirilir.
    9 elemanı, 7'den büyük olduğu için sağa, 8'den büyük olduğu için sağına geçer.
    4 elemanı, 7'den küçük olduğu için sola gelerek 3 elemanının sağına gelir.
    2 elemanı, 7'den küçük olduğu için sola ve sırasıyla takip ederek 3 elemanının soluna yerleştirilir.


https://app.patika.dev/dividefurkan
