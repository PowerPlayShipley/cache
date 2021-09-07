# PowerPlayShipley Fines Cache

This is the cache/store for the fines system. To save time, and keep a history things will
be saved with git using a mix of JSON and YAML

## Format

```shell
~/leagues -> Hold list of folders with leagues
~/leagues/<league> -> The league name
~/leagues/<league>/config.yml -> The league details
~/leagues/<league>/<year> -> The League year, or name etc
~/leagues/<league>/<year>/config.yml -> The years config
~/leagues/<league>/<year>/history -> The history of the year
~/leagues/<league>/<year>/history/<wk#>.json -> The file to hold the history files
```
