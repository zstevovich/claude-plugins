# zstevovich — Claude Code marketplace

Katalog Claude Code pluginova i skillova. Ovaj repo sadrži **samo spisak** — svaki plugin živi u svom repozitorijumu, sa svojom istorijom, testovima i verzijama.

## Dodavanje

```
/plugin marketplace add zstevovich/claude-plugins
```

Posle toga se pluginovi instaliraju po imenu:

```
/plugin install serbian-copy@zstevovich
```

## Šta je u katalogu

| Plugin | Šta radi |
|---|---|
| [serbian-copy](https://github.com/zstevovich/serbian-copy) | Pisanje i lektura srpskog marketinškog copy-ja — sajt, deck, PR, social, slogani |

## Odnos prema `claude-apd`

[APD](https://github.com/zstevovich/claude-apd) ima sopstveni marketplace pod imenom `zstevovich-plugins`, koji se dodaje preko `zstevovich/claude-apd` i nastavlja da radi nepromenjeno. Ovaj katalog je zaseban i nosi drugo ime (`zstevovich`), pa se dva ne sudaraju — Claude Code vodi marketplace-ove po imenu, ne po repou. Ko koristi oba, dodaje oba; ništa se ne mora migrirati.

## Licenca

MIT — v. [LICENSE](LICENSE). Licence pojedinačnih pluginova stoje u njihovim repozitorijumima.
