# WollterLive F-Droid repozitář

Přidání do F-Droid klienta:

```
https://wollterlive.github.io/fdroid/repo?fingerprint=11B7FB5AC8F561697D9618AB13B3B57C510966981D7F248CA35E3C7FFC32D3AA
```

Otisk klíče: `11B7FB5AC8F561697D9618AB13B3B57C510966981D7F248CA35E3C7FFC32D3AA`

## Přidání / aktualizace aplikace

1. Zkopíruj APK do `fdroid/repo/` (např. `cz.hra.body_30.apk`). Nová verze musí mít vyšší `versionCode` a stejný podpis.
2. Volitelně uprav popis v `fdroid/metadata/<balíček>.yml`.
3. `git add . && git commit -m "..." && git push` – GitHub Actions vygeneruje a podepíše index a nasadí ho na GitHub Pages.

Podepisovací klíč repozitáře je uložen v GitHub Secrets (`FDROID_KEYSTORE`, `FDROID_KEYSTORE_PASS`).
