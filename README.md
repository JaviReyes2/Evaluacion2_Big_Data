# Evaluacion2_Big_Data  
**Integrantes: Javiera Reyes**

---

### 1.- Se accedió a Google Cloud Platform y, dentro del servicio Cloud Storage, se creó el bucket denominado `javiera-reyess`. Posteriormente, se cargó el archivo `ufo_sighting.csv` al bucket, verificando que la carga fuera exitosa en la interfaz del navegador de objetos.  
![image](https://github.com/user-attachments/assets/07a8dd44-c449-4fb4-85a2-d4f5cac31d0d)

---

### 2.- Creación del dataset en BigQuery  
En la plataforma Google Cloud, se procedió a crear un nuevo dataset denominado `ovni` dentro del servicio BigQuery Studio. Esta acción permitió organizar y preparar el entorno para la posterior carga y análisis de los datos de avistamientos.  
![image](https://github.com/user-attachments/assets/d668d37d-0a85-4c4d-a0b0-d41f4a43a974)

---

### 3.- Carga del archivo a BigQuery  
Se procedió a cargar el archivo `ufo_sighting.csv` desde el bucket de Cloud Storage al dataset `ovni` en BigQuery. Para ello, se creó la tabla denominada `avistamientos`, utilizando la opción de autodetección de esquema para facilitar el proceso y asegurar la correcta estructura de los datos.  
![image](https://github.com/user-attachments/assets/5364cb5d-afe7-4e30-87bc-0dae4af582a9)

---

### 4.- Visualización y validación del dataset  
Una vez cargado el archivo, se visualizó el contenido de la tabla `ufo_sighting` para verificar la correcta importación de los datos. Se confirmó la presencia de las columnas clave y la variedad de categorías en los principales campos, asegurando así la integridad y disponibilidad del dataset para su posterior análisis.  
![image](https://github.com/user-attachments/assets/6e700af1-2040-42b5-9db7-f7830a14c617)

---

### 5.- Validación del esquema y perfilado de datos  
Durante la etapa de validación en Cloud Dataprep, se comprobó que el esquema de la tabla fuera correcto y que no existieran cambios inesperados. El perfil de transformación indicó que el 99,6% de los valores eran válidos, con solo un 0,4% de valores incompatibles y 0% de datos faltantes, asegurando así la calidad y completitud de los datos para el análisis posterior.  
![image](https://github.com/user-attachments/assets/f7d18383-59d2-40cb-acf3-7dd1ee75c95f)

---

## Gráficos

---

### Distribución de avistamientos por país  
Se elaboró un gráfico de torta para visualizar la distribución de los avistamientos entre los cuatro países con mayor cantidad de reportes: Estados Unidos (us), Canadá (ca), Australia (au) y Reino Unido (gb). Cada país representa un 25% del total, lo que evidencia una alta concentración de registros en estos territorios, según los datos disponibles.  
![WhatsApp Image 2025-06-23 at 19 03 01](https://github.com/user-attachments/assets/391af669-20d5-4d88-b84b-56921929b91e)

---

### Tendencia de avistamientos por año  
El gráfico muestra la evolución anual del número de avistamientos reportados. Se observa un aumento sostenido hasta alcanzar un peak alrededor de los años 2012-2013, seguido de una disminución progresiva en los años más recientes. Esta visualización permite identificar fácilmente los periodos con mayor frecuencia de reportes y analizar posibles patrones o cambios en el tiempo.  
![WhatsApp Image 2025-06-23 at 19 06 06](https://github.com/user-attachments/assets/eccb5071-e997-4f21-94ad-3a3a7227134d)

---

### Distribución geográfica de los avistamientos  
El mapa interactivo muestra la localización y cantidad de avistamientos reportados a nivel mundial. Se observa una mayor concentración de reportes en Norteamérica, especialmente en Estados Unidos y Canadá, aunque también existen registros relevantes en Europa, Australia y algunas zonas de Sudamérica y África. Este tipo de visualización permite identificar regiones con mayor actividad y facilita el análisis espacial de los fenómenos reportados.  
![WhatsApp Image 2025-06-23 at 19 11 57](https://github.com/user-attachments/assets/6159d413-9a50-441c-81b8-089657183921)

---

### Distribución de avistamientos por forma en Estados Unidos  
Se realizó un análisis descriptivo para determinar las formas más comunes de avistamientos reportados en Estados Unidos. Los resultados muestran que la categoría "light" es la más frecuente, con 5.440 registros, seguida de "triangle" y "circle". El gráfico y la tabla resumen los cinco tipos principales, permitiendo visualizar claramente la predominancia de objetos luminosos en los reportes.  
![WhatsApp Image 2025-06-23 at 18 56 44](https://github.com/user-attachments/assets/5e7e87fb-1ead-4d74-852a-5afafa1417d8)

