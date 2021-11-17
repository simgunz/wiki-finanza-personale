# DataEng Wiki

Sito live: https://simgunz.github.io/wiki-finanza-personale/

## Installazione e avvio locale

Installare le dipendenza eseguendo:

```bash
pipenv sync
```

Per eseguire il server HTTP locale e visualizzare la wiki eseguire:

```bash
pipenv run mkdocs serve -a localhost:9000
```

## Pubblicazione online

Per pubblicare online

```bash
pipenv run mkdocs gh-deploy
```

Dopo qualche minuto le modifiche dovrebbero essere live

