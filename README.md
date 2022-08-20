https://app.patika.dev
### 3.ODEV-BINARY-SEARCH-TREE
 
## Proje 3
# Soru) [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

  # 1-aşama: 7 sayısı ilk değer olduğu için root seçilir. 5 değeri root değerinden küçük olduğu için sol tarafa yazılır.
  # 2-aşama: 1 değeri 7'den küçüktür, sola tarafa gider, 5'ten de küçüktür o yüzden 5'in sol altına yazılır.
  # 3-aşama: 8 değeri 7'den büyüktür, root'un sağ tarafına yazılır.
  # 4-aşama: 3 değeri 7'den küçüktür, 5'ten küçüktür ama 1'den büyüktür, bu yüzden 1'in sağ tarafına yazılır.
  # 5-aşama: 6 değeri 7'den küçüktür, 5'ten büyüktür, bu yüzden 5'in sağına yazılır.
  #  6-aşama: 0 değeri 7'den, 5'ten ve 1'den küçüktür, bu yüzden 0'ın soluna yazılır.
  # 7-aşama: 9 değeri 7'den ve 8'den büyüktür, bu yüzden 8'in sağına yazılır.
  # 8-aşama: 4 değeri 7'den ve 5'den küçüktür, 1'den ve 3'ten büyüktür, bu yüzden 3'ün sağına yazılır.
  #  son-aşama: 2 değeri 7'den ve 5'den küçüktür, 1'den büyük ama 3'den küçüktür, bu yüzden 3'ün soluna yazılır.

                   7
                  / \
                 5   8
                / \    \
               1   6    9
              / \
             0   3
                / \
               2   4

