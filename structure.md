#Database AutoUsate

## (table) Auto:
- id                            INT PRIMARY KEY UNIQUE NOTNULL<!-- 123123 -->
- marca                         VARCHAR(20) NOTNULL<!-- Fiat, Opel -->
- modello                       VARCHAR(50) NOTNULL<!-- Panda, Astra, Aventador -->
- tipologia                     VARCHAR(30) <!-- Berlina, SUV, -->
- colore                        VARCHAR(30) <!-- Bianco Perla, Grigio Metallizato -->
- paese_di_origine              VARCHAR(30) <!-- Italia, Romania, Grecia -->
- anno_di_produzione            YEAR NOTNULL<!-- 2012, 2019 -->
- data_di_immatricolazione      DATE <!-- 13-1-2016 -->
- prezzo                        FLOAT(7,2) NOTNULL<!-- 15000€ -->
- kilometri                     INT NOTNULL<!-- 1000000 -->
- carburante                    VARCHAR(30) NOTNULL<!-- diesel,GPL, ibrida -->
- cambio                        VARCHAR(20) NULL<!-- manuale, autmatico -->
- trazione                      VARCHAR(20) NULL<!-- anteriore, 4x4 -->
- cilindri                      TINYINT NULL<!-- 3,4,5 -->
- cilindrata                    SMALLINT NOTNULL<!-- 929 cc, 2130 cc -->
- peso                          SMALLINT NOTNULL<!-- 1570 kg, 2100 kg -->
- omologazione                  VARCHAR(10) NOTNULL<!-- Euro 6, Euro 4, Euro 3 -->
- porte                         TINYINT NOTNULL<!-- 2,3,5 -->
- posti                         TINYINT NOTNULL<!-- 2,5 -->
- marce                         TINYINT NULL<!-- 5,6,7 -->
- condizioni                    VARCHAR(20) NOTNULL<!-- perfette, leggermente danneggiato -->

