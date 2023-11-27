## 2. Mi a SMoRES irányelv? Milyen előnyei vannak az állapotgép struktúrának a szekvenciális programozással szemben? Mikor érdemes párhuzamosan futó ciklusokat használni?

- SMoRES
  - **S**calable — skálázható
  - **Mo**dular — moduláris
  - **R**eusable — újrafelhasználható
    - forráskód aktuális alkalmazásról leválasztható, hogy egy újabb projektben is fel lehessen használni
      - (=kellően absztrakt)
  - **E**xtensible — bővíthető
    - mennyire nehézkes egy új funkció hozzáadása?
  - **S**imple — egyszerű
    - lehetséges megoldások közül a legegyszerűbb implementálása

- állapotgép vs szekvenciális programozás
  - ???
  - saját kútfőből…
  - szekvenciális programozásnál a lépések végrehajtási sorrendjének változtatása nehézkes
  - új állapot hozzáadása és a meglévő szerkezetbe csatolása könnyű
    - csak az érintett elemeket kell újraírni/kiegészíteni, nem a teljes modult

- párhuzamosan futó ciklusok használatának előnyei
  - független adatokkal dolgozás
  - reszponzivitás lehetővé tétele (tehermentesítés)
