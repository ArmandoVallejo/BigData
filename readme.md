# Instrucciones para el Proyecto

> ⚠️ **Advertencia:** Antes de ejecutar el proyecto, asegúrate de que **Elasticsearch** esté corriendo en tu sistema.


1. Clona el repositorio:
    ```bash
    git clone https://github.com/ArmandoVallejo/DataScience.git
    ```

2. Descarga el archivo con los datos de este link:
    [Descargar archivo desde Google Drive](https://drive.google.com/file/d/1p-PAruCzOgC8GewpZ6tD0pZOe27HqjLO/view?usp=sharing)

3. Pon el archivo en el repositorio que acabas de clonar.

4. Crea un entorno virtual:
    ```bash
    python -m venv .venv
    ```

> ⚠️ **Precaución:** La versión de Elasticsearch debe coincidir con la versión del cliente de Python que instalas.

5. Instala las dependencias:
    ```bash
    pip install -r requirements.txt
    ```

6. Verifica la version de ElasticSearch correspondiente a instalar accediendo a localhost:9200 en el navegador


7. Instala la version de ElasticSearch correspondiente
    ```bash
    pip install elasticsearch==x.x.x
    ```
