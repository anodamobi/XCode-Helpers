# XCode-Helpers

Script that creates XCode modules from templates. Put your 

## Usage

Example:

```
./structure.py \
  --template ~/Development/ANODA/ModuleTemplate/ \
  --prefix PP \
  --project TestProj \
  --module PriceAlert
```

### Variables

`<%prefix%>` — taken from the --prefix parameter (ex. `PP`)

`<%prefixLower%>` — same as previous but first letter always lower (ex. `pP`)

`<%project%>` — taken from the --project parameter (ex. `TestProj`)

`<%projectLower%>` — same as previous but first letter always lower (ex. `testProj`)

`<%module%>` — taken from the --module parameter (ex. `PriceAlert`)

`<%moduleLower%>` — same as previous but first letter always lower (ex. `priceAlert`)