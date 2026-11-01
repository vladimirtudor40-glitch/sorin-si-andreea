# Sorin & Andreea

Lista invitaților la nunta lui Sorin și a Andreei: o pagină în stil de planșă de arhitectură, cu piramidele de la Giza, motive muzicale și detalii de cod.

Datele vin live din Google Sheet-ul nunții (endpoint-ul public `gviz` CSV). Dacă sheet-ul nu poate fi citit, pagina folosește copia salvată în `index.html`.

## Rulare locală

Deschide `index.html` într-un browser sau pornește un server static:

```bash
py -3 -m http.server 5178
```

## Publicare

Settings → Pages → Deploy from a branch → `main` / root.
