# Limpieza del Historial de Commits con Git Rebase

## Pasos realizados:
1. Realicé tres commits con mensajes poco claros: "Arreglos", "Cambios", "Actualización de cosas".
2. Usé `git rebase -i HEAD~3` para modificar el historial:
   - Cambié los mensajes a:
     - "Añadido archivo archivo1.txt con su contenido inicial"
     - "Fusionado: Añadidos archivo2.txt y archivo3.txt con nuevas líneas de código".
   - Fusioné commits innecesarios (`squash`) para mejorar la claridad.
3. Hice un `git push --force` para actualizar el historial en el repositorio remoto.
4. git push --set-upstream origin main, para vincular la rama local main con la rama remota del repositorio github.
