# Vibecode

## Sesong

Se hva som er i sesong i Norge nå, hvor du får tak i det, oppskrifter, handleliste og vinforslag. Ingen innlogging.

Appen ligger i `sesong/`. Den kan legges på hjemskjermen på iPhone (Safari → Del → Legg til på Hjem-skjerm).

### Oppdatere appen

Kilden er `tools/sesong-source.html`. Etter en endring, kjør:

```
python3 tools/build.py
```

Det lager `sesong/index.html`, app-ikoner, manifest og offline-støtte (`sw.js`).

Bildene i `sesong/img/` er gratis bilder. Fotografer og lisenser står under «Bildekreditering» nederst i appen.
