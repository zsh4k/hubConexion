# hubConexion

Es un software escrito en bash para probar la conexion a github a travez de la consola y git.
Crea una Llave ssh nueva en caso de no tener.
Y finalmente puedes conectarte a github con git, configurando la nueva llave en tu cuenta.

## Instalacion

```bash
u=/usr/bin;n=hubConexion;cd $u;curl -O https://raw.githubusercontent.com/zsh4k/$n/main/$n;chmod +x $n;cd
```

## Uso

### Iniciar:

```bash
hubConexion
```

### Probar conexion a github:

```bash
hubConexion test
```
