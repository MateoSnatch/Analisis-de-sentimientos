
# Análisis de Llamadas Telefónicas - Minería de Datos No Estructurados

## Descripción
Este proyecto analiza las llamadas telefónicas de un concesionario del sector automotriz. Se utilizan técnicas de minería de datos no estructurados para transcribir, procesar y analizar las conversaciones telefónicas con el objetivo de mejorar la calidad del servicio al cliente.

### Objetivos:
1. Transcribir audios a texto para convertirlos en datos procesables.
2. Aplicar técnicas de limpieza de datos, eliminación de stopwords y lematización.
3. Analizar sentimientos y clasificar las interacciones en positivas, negativas y neutrales.
4. Generar insights para mejorar procesos de atención al cliente.

---

## Nota Importante  
Este proyecto es un **modelo a escala**. Para obtener resultados más precisos y aplicables a un nivel industrial, es necesario mejorar los modelos utilizados y enriquecerlos con datos adicionales.  

---

## Resultados
### Modelos de Clasificación:
1. **Regresión Logística**
   - Precisión llamadas positivas: 73.6%
   - Precisión llamadas negativas: 75%
   - Precisión llamadas neutrales: 60.2%

2. **Máquinas de Soporte Vectorial (SVM)**
   - Precisión llamadas positivas: 81.1%
   - Precisión llamadas negativas: 72.6%
   - Precisión llamadas neutrales: 67.5%

En los casos donde los modelos divergieron, se optó por los resultados de SVM por su mayor precisión general.

---

## Uso del Proyecto

### Requisitos Previos:
1. Instalar Python 3.8 o superior.
2. Instalar las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

3. Descargar el archivo CSV necesario desde este [enlace a Drive](https://drive.google.com/drive/folders/1zKEPnngPGV3G_5XQHJBZB3kb8IFGprjT?usp=drive_link).

### Ejecución:
1. Coloca el archivo CSV en el directorio raíz del proyecto.
2. Ejecuta el script principal:
   ```bash
   python main.py
   ```

3. Los resultados estarán disponibles en los archivos generados por el script.
