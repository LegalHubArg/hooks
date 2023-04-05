# Hooks
En este repositorio se van a guardar todos los hooks que se hagan y/o configuraciones que se necesiten y se utilicen en los diferentes proyectos.
**Por favor no modificar las configuraciones por defecto**

## Instalación
La instalacción en sencilla y debemos seguir estos pasos.

```bash
pip install pre-commit
cd path/to/repo
cp this/repo/.pre-commit-config.yaml .
pre-commit install
git config commit.template this/repo/.gitmessage.txt
```

## Uso
Para utlizar simplemente debemos en linea de comandos ejecutar

```bash
git add [files]
git commit
```

y se nos abrirá un editor de texto, o el editor de texto seleccionado, con el modelo de commit a completar.
Tener en cuenta que si el pre-commit realiza cambios en los archivos debemos volver a ejecutar el comando git add.

Enjoy it.
