Tenemos una serie de directorios.

El de configserver hace una configuracion local

El de pluralsight-spring-cloudconfig es simplemente el repo de donde bebemos el properties de configserver-git
(que va a ser donde levantemos nuestro servidor de configuracion)

El de config-client va a ser un microservicio que va a llamar al config server para enseñarnos cuales son las propiedades
dependiendo del entorno que utilicemos.