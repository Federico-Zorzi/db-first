| name               | type        | attributes                          | key     | notes                         |
| ------------------ | ----------- | ----------------------------------- | ------- | ----------------------------- |
| id                 | BIGINT(20)  | NO NULL - AUTO_INCREMENT - UNSIGNED | PRIMARY | 1,2,3...                      |
| brand_name         | VARCHAR(30) | NO NULL                             |         | "Fiat", "Ford", "Audi"        |
| model_name         | VARCHAR(30) | NO NULL                             |         | "500", "Puma", "A3"           |
| kilometers         | MEDIUMINT   | NO NULL - UNSIGNED                  |         | 120000                        |
| fuel               | ENUM        | NO NULL                             |         | "diesel", "benzina", "metano" |
| cc                 | SMALLINT    | NO NULL - UNSIGNED                  |         | 120                           |
| doors_number       | TINYINT     | NO NULL                             |         | 4                             |
| transmission       | ENUM        | NULL                                |         | "manuale" , "automatico"      |
| color              | VARCHAR(15) | NULL                                |         |                               |
| condition          | CHAR(1)     | NO NULL                             |         | "o"=>ottime; "p"=>pessime     |
| price              | MEDIUMINT   | NO NULL - UNSIGNED                  |         | 15000                         |
| production_date_at | DATE        | NO NULL                             |         | 2020-05-11                    |
