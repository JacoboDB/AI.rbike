# AI.rbike
Proyecto realizado durante la segunda edición de Saturdays.AI Guadalajara
por el equipo Turquesa.

## Integrantes del Equipo
- [Raul Garcia Rojas](mailto:raulgr@gmail.com)
- [Jacobo Domínguez Balderrama](https://www.linkedin.com/in/jacobodominguezbalderrama/)
- [Norma Adriana Tapia Muñoz](https://www.linkedin.com/in/norma-adriana/)
- [Kimberly Celeste Uribe López](https://www.linkedin.com/in/kimberly-celeste-uribe-lópez/)
- [Edwin Efrain Jimenez Lepe (mentor)](https://www.linkedin.com/in/edwinjimenezlepe/)

El proceso y la experiencia ha sido documentada en Medium
[Parte 1](https://medium.com/@kimberlyuribe/ai-rbike-renovar-el-enfoque-del-uso-de-bicicleta-a-través-del-análisis-de-datos-y-su-impacto-en-aff584116146)

## Descripción
Utilizando datos abiertos del sistema MiBici + calidad de aire de la ZMG, se hace un
análisis de la relación entre la calidad de aire y el uso de bicicletas. Con esto se pretende
crear un modelo de Machine Learning con la finalidad de demostrar que a un mayor uso
de bicicleta como medio de transporte se tiene como consecuencia una mejora en la
calidad de aire de la zona.

## Datos
Los datos crudos que se usaron durante el EDA y preprocesamiento se pueden obtener en los siguientes enlaces

### NY
- [Citibike - Sistema público de bicicletas](https://s3.amazonaws.com/tripdata/index.html)
- [OpenAQ - Datos sobre calidad del aire](http://openaq-data.s3.amazonaws.com/index.html) 

Para extraer los datos de calidad del aire es necesario seguir [esta guía](https://medium.com/@openaq/how-in-the-world-do-you-access-air-quality-data-older-than-90-days-on-the-openaq-platform-8562df519ecd)
### Guadalajara
- [MiBici  - Sistema público de bicicletas](https://www.mibici.net/es/datos-abiertos/)
- [SEMADET - Datos sobre calidad del aire](https://datos.jalisco.gob.mx/dataset/bases-de-datos-historicas-de-la-calidad-del-aire)

### Boston
- [Bluebikes  - Sistema público de bicicletas](https://s3.amazonaws.com/hubway-data/index.html)
- [AQS API - Datos sobre calidad del aire](https://aqicn.org/data-platform/register/)

Para extraer los datos de calidad del aire es necesario seguir [esta guía](https://aqs.epa.gov/aqsweb/documents/data_api.html#signup) 