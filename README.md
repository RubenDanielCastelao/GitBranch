# Comandos usados

## Paso A

### Crear el proyecto,

Usar los comandos:
```
git commit -m "A"
git push origin main
```
## Paso B

### Modificar la rama main,

y usar los siguientes comandos:
```
git commit -m "B"
git push origin main
```

## Paso C

### Crear la rama exp,

```
git branch exp
```

### haver checkout a esta rama y hacer alguna modificación,

```
git checkout exp
```
y subirlo con:
```
git commit -m "C"
git push origin main
```

## Paso E

### Volver a la rama main
```
git checkout main
```
### modificar algo en este rama,

y hacer el commit:
```
git commit -m "E"
git push origin main
```

## Paso D

### Hacer el checkout a la rama exp
```
git checkout exp
```
### hacer modificaciones y commit,

```
git commit -m "D"
git push origin main
```

### hecho esto se procede al merge,

para lo que haremos checkout a main, y luego el merge.
```
git checkout main
git merge exp
```
## Paso F

### Hacer el ultimo commit y push.

```
git commit -m "F"
git push origin main
```

### se añade finalmente un ultimo commit con el Readme.

```
git commit -m "Readme"
git push origin main
```
