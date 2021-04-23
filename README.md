
# Kavárna BENG!

- Využívám SASS (Pokud to nevadí),
  - Ale v adresáři `dist` je hezky čitelný výstup v CSS
- Provizorně je web dostupná na mém serveru na adrese: [http://kangaroo.tenvalka.eu/](http://kangaroo.tenvalka.eu/)
> Verze odevzdaná 21.4. je dostupná na: http://kangaroo.tenvalka.eu/ .
> 
> Nejnovější verze je dostupná na http://v2.kangaroo.tenvalka.eu/ .
> 
## Nastaveni projektu

1. Instalace závislostí (sass, cpx, del)
```sh
npm install # nebo
yarn
```

2. Ručně nahrát fonty do adresáře `static/font`
   - TriviaSansRegular.woff
   - TriviaSansRegular-Bold.woff
   - Fonty spadají nejspíše pod placenou licenci (Nechci riskovat)

3. Kompilace a vytvoření kompletního adresáře s distribucí webu
```sh
npm run build # nebo
yarn build
```

