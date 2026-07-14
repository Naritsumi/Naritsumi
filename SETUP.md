# Instalación

1. Copia `README.md` a la raíz del repositorio de perfil `Naritsumi/Naritsumi`.
2. Copia la carpeta `.github/workflows/` completa.
3. Confirma los archivos en la rama `main`.
4. Abre la pestaña **Actions** del repositorio.
5. Ejecuta manualmente:
   - **Generate contribution snake**
   - **Generate 3D contribution calendar**
6. Espera a que ambos workflows terminen correctamente.
7. Recarga tu perfil.

## Notas

- La serpiente se publica en la rama `output`.
- El calendario 3D se genera en `profile-3d-contrib/`.
- Durante la primera ejecución, esas dos imágenes pueden aparecer rotas.
- Los workflows se actualizan automáticamente una vez al día.
- No necesitas crear secretos adicionales: utilizan `GITHUB_TOKEN`.
- Si la rama principal se llama de otra forma, cambia `main` en `snake.yml`.
