# DB Init

Nahraj si jednoduchou testovací databázi, se kterou budeš pracovat.

Úkoly

1. Stáhni si databázi [world.sql](https://raw.githubusercontent.com/morenoh149/postgresDBSamples/master/worldDB-1.0/world.sql)
1. Ověř si, že ti běží databáze a nevypla se ti během restartů počítače.
1. Importuj databázi: `psql -f world.sql -U root -h 127.0.0.1 -p <port> <jmeno-databaze>`. Tohle by ti mělo sedět s `compose.yaml`, jak jsi to nastavil minule.
1. Ověř, že v dbeaveru vidíš nové tabulky (např. `public -> Tables -> city`)
