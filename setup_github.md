# Procedimiento completo para usar GitHub

## 1. Crear repositorio

1. Entrar a https://github.com/
2. Iniciar sesión.
3. Seleccionar **New repository**.
4. Nombre sugerido: `retroalimentacion-pm-lasalle-bajio`
5. Visibilidad sugerida:
   - **Private** si se trabajará solo con equipo interno.
   - **Public** si no hay datos sensibles y se desea mayor apertura.
6. Crear el repositorio.

## 2. Subir archivos

1. Descargar el paquete ZIP entregado.
2. Descomprimirlo.
3. Subir todo el contenido al repositorio:
   - `.github/ISSUE_TEMPLATE/`
   - `docs/`
   - `README.md`
   - `guia_docentes.md`
   - `setup_github.md`

Puede subirse desde la interfaz web de GitHub con **Add file > Upload files**.

## 3. Activar GitHub Issues

1. Ir a **Settings**.
2. Entrar a **Features**.
3. Verificar que **Issues** esté activado.

## 4. Probar plantillas

1. Ir a la pestaña **Issues**.
2. Presionar **New issue**.
3. Deben aparecer:
   - Observación puntual
   - Revisión general por asignatura
   - Acuerdo de reunión

## 5. Crear etiquetas

Ir a **Issues > Labels** y crear las etiquetas recomendadas en el README.

## 6. Activar GitHub Pages

1. Ir a **Settings > Pages**.
2. En **Build and deployment**, seleccionar:
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/docs`
3. Guardar.
4. GitHub generará una URL pública para la página de bienvenida.

## 7. Compartir con docentes

Compartir la URL de GitHub Pages o directamente la URL:

`https://github.com/USUARIO/REPOSITORIO/issues/new/choose`

## 8. Captura de respuestas

Cada respuesta se guarda como un issue. Esto permite:
- comentar;
- asignar responsable;
- clasificar por etiquetas;
- cerrar cuando se atienda;
- conservar trazabilidad.

## 9. Limitación importante

GitHub Issues requiere cuenta de GitHub. Si algunos docentes no tienen cuenta, se recomienda que un relator capture sus observaciones durante la reunión y las registre posteriormente.
