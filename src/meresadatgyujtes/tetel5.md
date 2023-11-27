## 5. Mit nevezünk beágyazott rendszernek? Mi a kemény valós idejű rendszer (hard real-time system (HRT))? Adjon példát kemény valós idejű rendszerre! Mi a puha valós idejű rendszer (soft real- time system (SRT))? Adjon példát puha valós idejű rendszerre

- Olyan speciális célú számítógépek, amelyeket konkrét feladat ellátására terveztek
- korlátozott számítási kapacitás és memória
- Egy operációs rendszer valós idejű, ha mindig engedélyezi programjainak, hogy azok adott időbeni korlátokon belül futtassák feladataikat
  - lehet esemény- vagy idővezérelt
- kemény valósidejű rendszer
  - katasztrofális következményekkel jár, ha nem tartjuk az időkorlátot
  - szigorúan definiált és betartott válaszidők jellemzik
  - pl. járműirányítás, atomreaktor
- puha valós idejű rendszer
  - az eredmény értékes az időkorláton túl is, de az idővel degradálódik
  - válaszidő betartása fontos, de a csúszás nem katasztrofális
  - pl. tranzakciós rendszerek, multimédia, IoT
