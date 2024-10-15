# Mi Proyecto

## Descripción
Este proyecto es un ejemplo de gestión de ramas utilizando Git. Contiene una rama principal `master` y una rama de trabajo `rama-nueva`.

## Estructura de Ramas
- **master**: Esta es la rama principal donde se mantiene el código estable.
- **rama-nueva**: Esta rama se utiliza para desarrollar nuevas características o realizar cambios antes de fusionarlos en `master`.

## Flujo de Trabajo
1. **Crear una nueva rama**:
   - Para realizar cambios, primero se debe crear y cambiar a una nueva rama:
     ```bash
     git checkout -b rama-nueva
     ```

2. **Realizar cambios**:
   - Haz los cambios necesarios en tu proyecto.

3. **Agregar y confirmar cambios**:
   - Agrega los cambios al área de preparación:
     ```bash
     git add .
     ```
   - Confirma los cambios:
     ```bash
     git commit -m "Descripción de los cambios realizados"
     ```

4. **Subir la nueva rama a GitHub**:
   - Sube la rama al repositorio remoto:
     ```bash
     git push -u origin rama-nueva
     ```

5. **Fusionar cambios en master**:
   - Cambia a la rama `master`:
     ```bash
     git checkout master
     ```
   - Fusiona los cambios de `rama-nueva`:
     ```bash
     git merge rama-nueva
     ```

6. **Subir cambios fusionados**:
   - Sube los cambios de `master` al repositorio remoto:
     ```bash
     git push origin master
     ```

## Contribuciones
Si deseas contribuir a este proyecto, siéntete libre de crear una nueva rama y realizar cambios. Luego, puedes crear un Pull Request para discutir tus cambios.

## Licencia
Este proyecto está bajo la Licencia MIT. Vilma Ponce

