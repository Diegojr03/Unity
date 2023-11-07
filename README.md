# Unity
Carpeta Unity

# README

## CalidadAjustes Script

Este script en C# para Unity, llamado "CalidadAjustes," gestiona la calidad gráfica en tiempo real mediante un menú desplegable. Utiliza `TMPro` y `UnityEngine`.

### Características:

1. **Dropdown y Variable de Calidad:**
   - `TMP_Dropdown` para seleccionar la calidad.
   - Variable `calidad` para almacenar el nivel.

2. **Inicio y Actualización:**
   - Inicialización en `Start`.
   - Recupera/calcula el nivel de calidad.
   - Método `AjustarCalidad` aplicado.

3. **Ajuste de Calidad:**
   - Método `AjustarCalidad` aplica la calidad.
   - `QualitySettings.SetQualityLevel` en tiempo real.
   - Persistencia con PlayerPrefs.

### Uso:

1. Agrega a un objeto en Unity.
2. Asigna `TMP_Dropdown` y configura.
3. El script gestiona y aplica los cambios.

### Notas:

- Ajusta la configuración de la escena en Unity.
- Personaliza el rango de calidad según necesites.

