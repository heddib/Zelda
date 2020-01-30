# Zelda
> Gère les langues du bot Hylia

### Structure du dossier pour les langues
```bash
ProjectDir/
└─── locales
     ├─── constants.json
     ├─── en_us
     │    ├─── error.json
     │    ├─── info.json
     │    └─── warn.json
     └─── fr_fr
          ├─── error.json
          ├─── info.json
          └─── warn.json
```


**TODO:**
- [X] Add support for a global constants across all locales.
- [X] Add support for variables in translated strings.
- [ ] Add support for using single file locales, for simple projects. Like:
  ```bash
    # Director Sturcture for locales
    ProjectDir/
    └──── Locales
          ├─── constants.json
          ├─── en_us.json
          └─── fr_fr.json
  ```
