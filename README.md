Primero cree el repo y hice un par de commit
```bash
git add main.java
git commit -m "Crear main"
```
Ahora el desarrollador crea su rama y su clase
```bash
git checkout -b saul
git add saul.java
git commit -m "crear saul.java"
```
Seguimos desarrollando el main y saul su clase...

Saul hace la PR en github y se la acepto, despues hago `git fetch` para traer sus cambios a mi repo local
```bash
git fetch
```
