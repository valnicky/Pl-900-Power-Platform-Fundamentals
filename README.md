| Práctica (7,5 horas)                          |                                                              |
| --------------------------------------------- | ------------------------------------------------------------ |
| Módulo 1:  Introducción a Power Platform      | N/A                                                          |
| Módulo 2: Introducción a Microsoft  Dataverse | 01 - Laboratorio: Modelado de datos                          |
| Módulo 3: Comience  con Power Apps            | 02 - Laboratorio: Cómo crear una aplicación de lienzo, parte 1 |
|                                               | 03 - Laboratorio: Cómo crear una  aplicación de lienzo, parte 2 |
|                                               | 04 - Laboratorio: Cómo crear una  aplicación basada en modelo |
|                                               | 05 - Laboratorio: Cómo crear un portal de  Power Apps        |
| Módulo 4: Comenzar con Power Automate         | 06 - Laboratorio: Cómo crear una solución automatizada       |
| Módulo 5: Comience con Power BI               | 07 - Laboratorio: Cómo crear un tablero simple               |
| Módulo 6: Comenzar con Power Virtual  Agents  | 08 - Laboratorio: Cómo crear un bot de chat básico           |

## Comandos para la configuración de Git desde cero para este repositorio
Nota: He creado una carpeta en la raiz de C:\ que se llama "local" y el GitHub un repositorio que se llama Pl 900 Power Platform-Fundamentals

```

git config --global user.name "Luz Tellez"
git config --global user.enmail "LuzJanneth@billyclasstime.com"
git config --list
cd C:\local
git init
git status
git add .
git commit -m "Fix the initial instructions to Power Platfornm practice"
git remote add origin https://github.com/LuzTellez/Pl-900-Power-Platform-Fundamentals.git
git branch -M main
git push -u origin main

```



Para recuperar los cambios desde el remoto:

```
git pull
```



Para Volver a "subir" los cambios del local al remoto:

```
git add.
git comit -m "Second fix"
git push
```

