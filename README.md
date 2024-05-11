
# Análisis del comportamiento electoral





```http
Variable dependiente
```
Cantidad de votos obtenidos por cada candidato en cada provincia en las elecciones presidenciales del 2021 en la segunda vuelta 

| Variable | Tipo     | Descripción                |
| :-------- | :------- | :------------------------- |
| `VOTOS_P1` | `númerico` | Cantidad de votos obtenidos en la segunda vuelta del Partido Político Nacional Perú Libre|
| `VOTOS_P2` | `númerico` | Cantidad de votos obtenidos en la segunda vuelta de Fuerza Popular |


```http
 Variable independiente
```

| Variable | Tipo     | Descripción                       |
| :-------- | :------- | :-------------------------------- |
| `IDH_2019`| `Cuantitativa continua` | Índice de Desarrollo Humano* |
| `porcentaje_ejecucion` | `cuantitativa continua` | |
| `Cantidad` | `númerico` | Cantidad de hogares sin acceso a Tecnología de Información y Comunicación, fuente Censo Nacional del 2017 |
| `año_2020` | `Cuantitativa continua` | Tasa de denuncias por comisión de delito según provincia por cada 10 000 mil habitantes del 2020** |
| `año_2021` | `Cuantitativa continua` | Tasa de denuncias por comisión de delito según provincia por cada 10 000 mil habitantes del 2020** |


*Los valores van desde 0 a 1, mientras mas cercano a 1 indica que la provincia tiene un mejor desarrollo humano. Toma en cosideración educación, salud y economía.
**Las denuncias son data recopilada de la PNP 



```http 
Offset --> Variables de control
```

| Variable | Tipo     | Descripción                       |
| :-------- | :------- | :-------------------------------- |
| `N_ELEC_HABIL`      | `Numerica` | Número de electores hábiles  |

