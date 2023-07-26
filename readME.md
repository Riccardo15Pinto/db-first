# DB-FIRST

## `Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.`

| `column`                                  | `data`      | `attributes`       |
| ----------------------------------------- | ----------- | ------------------ |
| id                                        | BIGINT      | PRIMARY_KEY UNIQUE |
| image                                     | VARCHAR     | NOT NULL           |
| brand `marca`                             | VARCHAR(20) | NOT NULL           |
| model `modello`                           | VARCHAR(15) | NOT NULL           |
| plate `targa`                             | VARCHAR(7)  | NOT NULL UNIQUE    |
| engine_supply `alimentazione`             | VARCHAR(20) | NOT NULL           |
| production_year `anno_produzione`         | YEAR        | NOT NULL           |
| first_enrollment `prima immatricolazione` | DATE        | NOT NULL           |
| car_body `carrozzeria`                    | VARCHAR(10) | NULL               |
| engine `motore`                           | VARCHAR(10) | NULL               |
| displacement `cilindrata`                 | VARCHAR(10) | NULL               |
| traction `trazione`                       | VARCHAR(3)  | NULL               |
| gear_box `cambio`                         | VARCHAR(10) | NULL               |
| gear `marce`                              | TYNINT      | NULL               |
| door `porte`                              | TYNINT      | NULL               |
| seats `posti `                            | TYNINT      | NULL               |
| top_speed `velocità max`                  | VARCHAR(7)  | NULL               |
| acceleration `accelerazione`              | VARCHAR(10) | NULL               |
| emissions `emissioni`                     | VARCHAR(10) | NULL               |
| approval `omologazione`                   | VARCHAR(10) | NULL               |
| combined consumption `consumo combinato`  | VARCHAR(10) | NULL               |
| emissions `emissioni co2`                 | VARCHAR(10) | NULL               |
