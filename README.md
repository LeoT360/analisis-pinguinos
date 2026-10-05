# Análisis de Pingüinos 🐧

Proyecto correspondiente al **Ejercicio Independiente Aplicado de la Semana 11**.

El objetivo de este proyecto es preparar un entorno de desarrollo en Python para futuros análisis de datos utilizando `pandas`, `matplotlib` y `seaborn`.

## 📁 Estructura del proyecto

```text
analisis_pinguinos/
│
├── .venv/
├── requirements.txt
├── analisis.py
└── README.md
```

> La carpeta `.venv` contiene el entorno virtual del proyecto y no es necesario modificar su contenido manualmente.

## ⚙️ Requisitos

Para ejecutar este proyecto se necesita tener instalado:

- Python 3.x
- Git (opcional, para clonar el repositorio)

## 🚀 Configuración del entorno

### 1. Clonar el repositorio

Si el proyecto se encuentra en GitHub, clónalo con:

```bash
git clone URL_DEL_REPOSITORIO
```

Luego, entra en la carpeta del proyecto:

```bash
cd analisis_pinguinos
```

### 2. Crear el entorno virtual

Desde la carpeta del proyecto, ejecuta:

```bash
python -m venv .venv
```

Esto creará un entorno virtual llamado `.venv`.

### 3. Activar el entorno virtual

**Windows (PowerShell):**

```powershell
.venv\Scripts\Activate.ps1
```

**Windows (CMD):**

```cmd
.venv\Scripts\activate
```

**macOS / Linux:**

```bash
source .venv/bin/activate
```

Cuando el entorno esté activo, aparecerá `.venv` al inicio de la línea de comandos.

### 4. Instalar las dependencias

Con el entorno virtual activado, instala todas las librerías necesarias utilizando el archivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

Este comando instalará `pandas`, `matplotlib`, `seaborn` y las dependencias necesarias con las versiones especificadas en el proyecto.

### 5. Verificar la instalación

Puedes comprobar que las librerías fueron instaladas correctamente ejecutando:

```bash
pip list
```

También puedes verificar específicamente las librerías principales:

```bash
pip show pandas matplotlib seaborn
```

## 🐧 Archivo `analisis.py`

El archivo `analisis.py` se encuentra preparado para desarrollar posteriormente el análisis del conjunto de datos de pingüinos.

Por el momento, el objetivo del ejercicio es únicamente configurar el entorno de desarrollo, por lo que el archivo puede permanecer vacío.

## 📦 Dependencias

Las principales librerías utilizadas en el proyecto son:

- **pandas:** manipulación y análisis de datos.
- **matplotlib:** creación de gráficos y visualizaciones.
- **seaborn:** creación de visualizaciones estadísticas.

Las versiones específicas de estas librerías y sus dependencias se encuentran en `requirements.txt`.

## 👥 Replicación del entorno

Para que otro desarrollador pueda trabajar con el mismo entorno, debe:

1. Clonar el repositorio.
2. Crear el entorno virtual `.venv`.
3. Activar el entorno virtual.
4. Ejecutar `pip install -r requirements.txt`.
5. Ejecutar o modificar `analisis.py` según las necesidades del proyecto.

De esta manera, todos los integrantes del equipo pueden utilizar las mismas versiones de las librerías instaladas.

## 📚 Semana 11

Este proyecto corresponde al **Ejercicio Independiente Aplicado de la Semana 11**.