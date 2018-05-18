
###SALUD MENTAL, REDES Y LEYES

####Descripción y motivación


![MostCommon](Word Art.jpeg )

    LINK DE LA EXPOSICIÓN EN YOUTUBE https://youtu.be/LAtcNc_2Seg

    Durante los ultimos años la preocupación respecto a la salud mental y la enfermedad mental ha aumentado a nivel mundial, a partir de esto surge la duda de si el aumento de esta preocupación ha impactado de alguna forma las politicas relacionadas a  este tema en Colombia.Es por esto que se plantea un analísis a algunos documentos propuestos por el Ministerio de Salud y Protección Social utilizando analísis de texto.


    Algunas preguntas  que motivaron el proyecto fueron:

    En el año 2013 se expidió la ley sobre salud mental. ¿Impactó de alguna forma las propuestas del ministerio?

    El Ministerio de Salud y Protección Social y la Secretaria de Salud Distrital  tienen cuentas activas en  twitter, se desea analizar a profundidad si realmente hay una inclusión del tema de salud mental por esta red social.

    ¿Ha aumentado el interés de los colombianos hacia temas relacionados a Salud Mental a partir de la expedición de la ley sobre salud mental?



    Herramientas utilizadas
     Se utilizó google trends para crear algunas grafícas sobre tendencias en google
     Scrapping Ministerio de Salud
![MostCommon](Dos.png )

    Para realizar scrapping de los datos utilicé la página del ministerio de salud, desde ahí descargue el proceso de rendición de cuentas de periodo antes y el periodo despúes del año.


Administrar y almacenar  los datos:

    Se utilizó R para realizar de forma más efectiva el Scrap de los tweets
    Usé 'Pandas' para crear un marco de datos para cada grupo de tweets, con matplotlib realicé grafícos 
    Además se utilizó la herramienta 
    Antes de hacer analísis de texto de los documentos utilicé las librerías 'string' y 'nltk'y eliminé la puntuación, convertí todo el texto a minúsculas y eliminé stopwords (en español).


####RESULTADOS

    Número de leyes: 100.

    Google Trends

    Se utilizó google trends para hacer una evaluación general sobre busquedas bibliografícas en google

    Aquí hay un ejemplo
    
    

####Twitter Ministerio de Salud 

Para esta parte del trabajo utilizamos R y Python el código lo puede encontrar [acá](http://localhost:8889/tree/OneDrive/Documentos/GitHub/MCPP_diego_ramirez/Proyectof/Twitter)

    El tweet con más likes es: 
    Por su compromiso social y aporte al cuidado de la salud, @MinSaludCol reconoce la labor de los 61.954 profesionales que  ejercen     la enfermería en Colombia https://t.co/xRLOF8XUq8
    El número de likes es: 88
    140 characters.

    El tweets con más retweets es: 
    RT @DapardAntioquia: #URGENTE | El @DapardAntioquia informa a la comunidad. https://t.co/NepBJ1tyGX
    Número de retweets: 787
    99 characters.

    Percentage of positive tweets: 5.0%
    Percentage of neutral tweets: 94.5%
    Percentage de negative tweets: 0.5%

####Twitter Secretaria de Salud Distrital

    El tweet con más likes es: 
    Reconocimientos #HechosDeCorazón 💓 valoran el trabajo a través de 6 categorías a todos los colaboradores del sector…       https://t.co/b7qBGgUQ0S
    El número de likes es: 22
    140 characters.

    El tweets con más retweets es: 
    RT @GobiernoBTA: Gobierno va con toda en el Reto #MáximaVelocidadGOB de @Ministerio_TIC 🏁🏆

    #FastGobierno es la escudería con la que estamo…
    Número de retweets: 106
    140 characters.
    Percentage of positive tweets: 2.5%
    Percentage of neutral tweets: 95.0%
    Percentage de negative tweets: 2.5%


 [MatPlotLib]("http://localhost:8889/notebooks/OneDrive/Documentos/GitHub/MCPP_diego_ramirez/Proyectof/LeyesMinSalud/MatPotLib.ipynb")] me   permitio realizar grafícs sobre la distribución de leyes y resoluciones.
 
     Distribución del número de resoluciones que tuvo un crecimiento exponencial durante  cuatro años (2011,2016) y disminuyó durante el ultimo año
![Resoluciones](Resoluciones.png )

Distribución de las leyes durante los ultimos 20 años, es importante fijarse en los picos de el año 2002 y 2009
![Leyes](Frecuencia.png )
 
 
 
 Por medio de nltk, string y pandas se realizó un analísis de la [LEY 1616 de 2013]("http://localhost:8889/tree/OneDrive/Documentos/GitHub/MCPP_diego_ramirez/Proyectof/LeyesSaludMental") 
 
 ![Leyes](Lexicley.png )
 
 Aquí esta el código [Dispersión]("http://localhost:8889/tree/OneDrive/Documentos/GitHub/MCPP_diego_ramirez/Proyectof/LeyesSaludMental") 
 

