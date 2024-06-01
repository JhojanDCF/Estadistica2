
# Análisis provincial de los determinantes del comportamiento electoral a partir de los resultados de segunda vuelta las elecciones presidenciales del 2021





```
Variable dependiente

```
Cantidad de votos total obtenidos por cada candidato en cada provincia en las elecciones presidenciales del 2021 en la segunda vuelta 

| Variable | Tipo     | Descripción                |
| :-------- | :------- | :------------------------- |
| `VOTOS_P1` | `Cuantitativa continua` | Cantidad de votos total obtenidos en la segunda vuelta del Partido Político Nacional Perú Libre|
| `VOTOS_P2` | `Cuantitativa continua` | Cantidad de votos total obtenidos en la segunda vuelta de Fuerza Popular |


```http
 Variable independiente

```

| Variable | Tipo     | Descripción                       |
| :-------- | :------- | :-------------------------------- |
| `IDH_2019`| `Cuantitativa continua` | Índice de Desarrollo Humano* |
| `porcentaje_ejecucion` | `Cuantitativa continua` | Porcentaje de Avance de Ejecución Presupuestal Anual del 2020** |
| `Cantidad` | `númerico` | Cantidad de hogares sin acceso a Tecnología de Información y Comunicación, fuente Censo Nacional del 2017 |
| `año_2020` | `Cuantitativa continua` | Tasa de denuncias por comisión de delito según provincia por cada 10 000 mil habitantes del 2020*** |
| `año_2021` | `Cuantitativa continua` | Tasa de denuncias por comisión de delito según provincia por cada 10 000 mil habitantes del 2020*** |


*Los valores van desde 0 a 1, mientras mas cercano a 1 indica que la provincia tiene un mejor desarrollo humano. Toma en cosideración educación, salud y economía. Es 
la ultima data actualizada antes de las elecciones presidenciales, no hay del 2020 por el COVID19.

** Se mide en porcentaje y agrupa a las municipalidades que conforman la provincia, su forma de medición es el gasto total del prespuesto ejecutado divido con los datos del presupuesto asignado.

***Las denuncias son data recopilada de la PNP 



```http 
Offset --> Variables de control

```

| Variable | Tipo     | Descripción                       |
| :-------- | :------- | :-------------------------------- |
| `N_ELEC_HABIL`      | `Cuantitativa continua` | Número de electores hábiles por provincia según el padron electoral del 2020 |

