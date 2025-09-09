# Universidad de Buenos Aires
### Carrera de Especialización en Inteligencia Artificial
### Cohorte 22 - Año 2025

<br>
<br>

# 👥 Análisis de datos - Grupo 2
Este repositorio contiene el material de resolución del Trabajo práctico integrador correspondiente al grupo 2. <br>
<br>
Este trabajo consiste en analizar y preparar los datos (sin entrenar un modelo) del dataset correspondiente a **Recorridos de bicicletas públicas del servicio Ecobici de la Ciudad Autónoma de Buenos Aires, para el año 2024.**

## Integrantes
- [SIU a2208] Ariel Matias Cabello <arielmcabello@gmail.com>
- [SIU a2213] Ignacio Agustin Costarelli <agustin@costarellisa.com.ar>
- [SIU a2214] Alex Martín Curellich <alexcurellich@gmail.com>

<br>
<br>

# 🔗 Links útiles
**Origen de los datos** (año 2024):
- BA Data. Secretaría de Transporte y Obras Públicas. Jefatura de Gabinete de Ministros: https://data.buenosaires.gob.ar/dataset/bicicletas-publicas

- Usuarios Ecobici 2024: https://data.buenosaires.gob.ar/dataset/bicicletas-publicas/resource/263fa064-bbf1-4e5f-a8ce-717cc2bd6075 (update al 3 de Septiembre de 2025)

- Recorridos Realizados 2024: https://data.buenosaires.gob.ar/dataset/bicicletas-publicas/resource/36846f29-05bb-4e05-b488-52916bbaae61 (update al 3 de Septiembre de 2025)
<br>
<br>

**Presentación** (solo visible para integrantes del grupo 2):
- https://docs.google.com/presentation/d/1gvLh4UPJtLsAMR7bpz-7ulUL6eTyhlfi5ry3QnrSrM8/edit?usp=sharing 

<br>
<br>

# ⚙️ Requerimientos
- Python >=3.11
- uv / Poetry / Pip / Conda
- Numpy, Pandas

<br>
<br>

# 🛠️ Instalación del entorno

## Usando Poetry (Recomendado)

1. **Instalar Poetry**:
   ```bash
   # En Windows (PowerShell)
   (Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | python -
   
   # O usando pip
   pip install poetry
   ```

2. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/ArielMatC/ceia-andd-g2
   cd ceia-andd-g2
   ```

3. **Instalar las dependencias**:
   ```bash
   poetry install
   ```

4. **Activar el entorno virtual**:
   ```bash
   poetry shell

   # Alternativa
   poetry env activate
   ```

## Usando pip (Alternativo)

1. **Crear un entorno virtual**:
   ```bash
   python -m venv venv
   # En Windows
   .\venv\Scripts\activate
   # En Linux/Mac
   source venv/bin/activate
   ```

2. **Instalar las dependencias**:
   ```bash
   pip install -e .
   ```

## Ejecutar Jupyter Lab

Una vez instalado el entorno, se puede ejecutar Jupyter Lab para trabajar con los notebooks:

```bash
# Con Poetry
poetry run jupyter lab

# Con pip (entorno virtual activado)
jupyter lab
```

