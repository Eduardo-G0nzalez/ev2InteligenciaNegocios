# BI_T2_GonzalezEduardo

Este proyecto contiene el notebook `BI_T2_GonzalezEduardo.ipynb` con análisis y modelos de machine learning. A continuación se indican los pasos para preparar el entorno y ejecutar el notebook.

## Requisitos previos
- Python 3.10 o 3.11 recomendado.
- Windows PowerShell (en Windows) o terminal equivalente en macOS/Linux.

## Configuración rápida (Windows)
1. Clona o descarga este repositorio en tu equipo.
   ```powershell
   git clone https://github.com/Eduardo-G0nzalez/ev2InteligenciaNegocios
   ```
2. Abre PowerShell en la carpeta del proyecto.
3. Crea un entorno virtual:
   ```powershell
   python -m venv .venv
   ```
4. Activa el entorno virtual:
   ```powershell
   .\.venv\Scripts\Activate.ps1
   ```
5. Instala dependencias:
   ```powershell
   pip install -r requirements.txt
   ```
6. Inicia JupyterLab y abre el notebook:
   ```powershell
   jupyter lab
   ```
   - Alternativa (Jupyter Notebook clásico):
     ```powershell
     jupyter notebook
     ```
7. En el navegador, abre `BI_T2_GonzalezEduardo.ipynb` y ejecuta las celdas (Kernel > Restart & Run All si deseas ejecutar todo de cero).

## Configuración en macOS/Linux (opcional)
1. Abre una terminal en la carpeta del proyecto.
2. Crea y activa un entorno virtual:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
3. Instala dependencias:
   ```bash
   pip install -r requirements.txt
   ```
4. Inicia JupyterLab:
   ```bash
   jupyter lab
   ```

## Dependencias
Las dependencias principales se listan en `requirements.txt` y fueron inferidas del notebook:
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- jupyterlab, ipykernel

Si ya tienes un entorno configurado con otras versiones, puedes ajustar los números de versión en `requirements.txt` según sea necesario.

## Notas y solución de problemas
- Si la activación del entorno virtual falla en PowerShell, habilita la política de ejecución para tu usuario:
  ```powershell
  Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
  ```
- Si `jupyter lab` no abre automáticamente el navegador, copia y pega la URL que aparece en la consola.
- Si aparecen errores de importación, verifica que el entorno virtual esté activado y que la instalación de dependencias haya finalizado sin errores.
