# Docker

Pro vývoj v databázích budeme používat kontejnery v Dockeru. Je to jednodušší, než instalovat několik instancí databáze.

Úkoly:

1. Zjisti, k čemu je docker (např https://docs.docker.com/get-started/overview/)
1. Nainstaluj si docker na svůj počítač
1. Vyzkoušej, že funguje (např pomocí `docker run --rm hello-world`)
1. Nauč se jaký je rozdíl mezi `image` a `container` (vše v odkazu výše)
1. Stáhni si kontejner s postgresem (image `postgres:16.2`)
1. Zjisti, co je to `port` a `volume`


# Docker compose
Docker compose je způsob jak definovat kontejnery, které spolu poběží.

Úkoly:

1. Projdi si https://docs.docker.com/compose/
1. Vytvoř si jednoduchý `compose.yaml`, ve kterém vytvoříš instanci databáze ([jednoduchý příklad](https://hub.docker.com/_/postgres))
1. Nezapomeň exposovat porty a volume.
1. Nezapomeň databázi nastavit heslo a jméno databáze
1. Spust kontejner (`docker compose up`)
