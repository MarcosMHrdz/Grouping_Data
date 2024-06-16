![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Laboratorio | Agrupación de datos

En esta práctica de laboratorio trabajaremos con el archivo `files_for_lab/abTesting.csv`. Consulte el archivo `case_study_ab_test.md` para comprender más sobre los datos recopilados. El archivo también tiene una descripción de los diferentes campos de datos que figuran en el archivo csv.

Asegúrese de guardar este cuaderno. Usaremos los resultados de esta práctica de laboratorio en la próxima práctica (para expresiones LOD). Usaremos esta práctica de laboratorio para prepararnos para la tarea del siguiente laboratorio.

### Instrucciones

Importe el csv a Tableau y responda las siguientes preguntas:

1. ¿Cuál es la distribución del número de participantes en cada etapa para la variación de control y la variación de prueba? Asegúrese de que los pasos del proceso estén en orden. El gráfico final se vería así: (No importa si usa el eje Y para los pasos del proceso)
    <detalles>
      <summary> Haga clic para ver la imagen </summary>

      <br />

      ![Participantes en cada etapa](https://education-team-2020.s3-eu-west-1.amazonaws.com/data-analytics/6.2_lab/participants_at_each_stage_control_vs_test.png)

    </detalles>
   
2. Ahora queremos comparar el número total de participantes para cada variación. Presta atención: ¿puedes tomar la suma de todos los pasos del proceso o no?
3. Duplique el trazado anterior en una hoja nueva. Ahora queremos encontrar el número total de participantes por género, es decir. ¿Cuál es el número de machos y hembras en cada variación? Puede filtrar las otras categorías de género presentes en los datos. (Seleccione solo hombres y mujeres en sus datos) El gráfico final se vería así:

    <detalles>
      <summary> Haga clic para ver la imagen </summary>

      <br />

      ![Total de participantes por género](https://education-team-2020.s3-eu-west-1.amazonaws.com/data-analytics/6.2_lab/total_number_of_participants_by_gender.png)

    </detalles>
    
4. Duplicar la hoja anterior. Ahora el objetivo es representar el número de participantes por género como porcentaje de los totales. Utilice para ello el cálculo de tabla rápida adecuado. Redondea los porcentajes a un punto decimal. La trama final quedaría así:

    <detalles>
      <summary> Haga clic para ver la imagen </summary>

      <br />
     
      ![Porcentaje total de participantes por género](https://education-team-2020.s3-eu-west-1.amazonaws.com/data-analytics/6.2_lab/percentage_total_participants_by_gender.png)

    </detalles>
    
5. Ya hemos visto cómo agrupar los datos creando un nuevo campo calculado (usando la declaración condicional `IF...ELSE`). Ahora crearemos grupos usando la opción "crear grupo" en Tableau. Crearemos diferentes grupos de edad y analizaremos el saldo medio de cada grupo. Sigue los pasos:

    - Haga clic en la flecha hacia abajo en `clnt_age` en el panel de dimensiones en el lado izquierdo. Vaya a crear y seleccione `grupos`:

    <detalles>
      <summary> Haga clic para ver la imagen del paso 1 </summary>

      <br />

      ![Crear grupos](https://education-team-2020.s3-eu-west-1.amazonaws.com/data-analytics/6.2_lab/create_groups.png)

    </detalles>


    - Cree los siguientes grupos: Edad de 17 a 30, 31 a 40, 40 a 55, 55 a 70 y 70 y más
    - Editar nombres de grupos:

    <detalles>
      <summary> Haga clic para ver las imágenes </summary>

      <br />

      - Imagen 1:

      ![Crear grupos](https://education-team-2020.s3-eu-west-1.amazonaws.com/data-analytics/6.2_lab/edit_group1.png)

      <br />
      
      - Imagen 2:

      ![Crear grupos](https://education-team-2020.s3-eu-west-1.amazonaws.com/data-analytics/6.2_lab/edit_group2.png)

    </detalles>

    - Trazar el saldo promedio de cada grupo. ¿Observas alguna tendencia?