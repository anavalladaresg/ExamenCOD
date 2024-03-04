# Proyecto Java

Este documento describe los pasos para trabajar con este repositorio.

## Pasos

1. **Fork del repositorio**: Realiza un fork del repositorio y clona tu proyecto forkeado.

2. **Crear rama 'readme'**: Crea una rama con el nombre 'readme' donde solo se almacenará este archivo. Usa el comando `git branch readme`.

3. **Cambiar a la rama 'readme'**: Usa el comando `git checkout readme`.

4. **Actualizar el 'readme'**: Añade los pasos que has realizado en este archivo.

5. **Cambiar a la rama 'interface'**: Muevete a la rama 'interface' para eliminar el commit indeseado.

6. **Eliminar el commit indeseado**: Usa el comando `git reset` para eliminar ese commit.

7. **Cambiar a la rama 'main'**: Cambia a la rama 'main' para hacer el merge.

8. **Merge squash**: Realiza un merge squash para que todos los cambios queden en un solo commit.

9. **Etiquetar el commit**: Etiqueta el commit como 'v1.0'.

10. **Añadir el archivo '.gitignore'**: Añade el archivo '.gitignore' olvidado con `git add .gitignore` y añádelo al commit con `git commit --amend`.