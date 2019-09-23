COMPANIES

1. Con Mongo he filtrado por aquellas compañías que tenían un capital mayor de 1M, aquellas que se han fundado en los últimos 10 años para buscar empresas "nuevas" y que no haya nulos en la columna oficinas, además he filtrado para que sean empresas tecnológicas filtrando por un category_code. 

2. Con la función geopoint he modificado la columna office y de tal manera en la que posteriormente me dejará filtrarlo en MongoDB Compass.

3. Obteniendo las columnas que quería para posteriormente deje filtrar y hacer el geonear en Tableau por los siguientes campos, City, latitude y longitude. (He renombrado algunas columnas para una mayor aclaración y he quitado los nulos de latitude y longitude para que no me de problemas). 

4. Una vez que ya lo tengo con el formato deseado, he contado qué ciudad es en la que hay más empresas que cumplan dichos requisitos y esta es Nueva York. Hasta aquí puede verse en mainpandasclean1. 

5. He buscado en New York los starbucks que hay alrededor a través de una API. Puede verse en mainpandasclean2

6. Se concatenan ambas tablas, con un geonear y finalmente por tableau se obtiene el punto final donde montar la empresa en base a los requisitos anteriormente descritos. Puede verse en mainpandasclean3

7. Tableau: https://public.tableau.com/profile/ignacio5899#!/vizhome/mongo-projectRocoBetegn/Sheet2?publish=yes
