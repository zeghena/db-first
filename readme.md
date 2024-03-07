| Campo           | Tipo dato | Descrizione                                 |
|-----------------|-----------|---------------------------------------------|
| ID              | Int       | Primary Key, Not Null, Unique               |
| Marca           | Varchar   | Not Null, Descrizione della marca dell'auto |
| Modello         | Varchar   | Not Null, Descrizione del modello dell'auto |
| Anno            | Int       | Not Null, Anno di fabbricazione dell'auto   |
| Chilometraggio  | Int       | Not Null, Chilometri percorsi dall'auto     |
| Prezzo          | Float     | Not Null, Prezzo di vendita dell'auto       |
| Descrizione     | Text      | Null, Descrizione aggiuntiva dell'auto      |

| ID | Marca      | Modello       | Anno | Chilometraggio | Prezzo | Descrizione                            |
|----|------------|---------------|------|----------------|--------|----------------------------------------|
| 1  | Toyota     | Corolla       | 2018 | 35000          | 12000.0| Ottimo stato, unico proprietario       |
| 2  | Ford       | Focus         | 2015 | 50000          | 9000.0 | Revisione appena effettuata            |
| 3  | BMW        | Serie 3       | 2017 | 40000          | 18000.0| Interni in pelle, sensori di parcheggio|
| 4  | Volkswagen | Golf          | 2016 | 45000          | 11000.0| Consumi bassi, ottima per la città     |