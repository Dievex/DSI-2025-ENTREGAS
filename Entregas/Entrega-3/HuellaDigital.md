| [![](https://img.shields.io/badge/-Inicio-FFF?style=flat&logo=Emlakjet&logoColor=black)](/README.md) [![](https://img.shields.io/badge/-Entrega_2-FFF?style=flat&logo=openstreetmap&logoColor=black)](/Entregas/Entrega-2/ModeloDeNegocio.md)  [![](https://img.shields.io/badge/-Entrega_3-FFF?style=flat&logo=openstreetmap&logoColor=black)](/Entregas/Entrega-3/HuellaDigital.md)  [![](https://img.shields.io/badge/-Entrega_4-FFF?style=flat&logo=openstreetmap&logoColor=black)]()|
|:-:|
# Huella Digital
|Alumno|Analisis Personal|
|-|-|
|Diego García|[Analisis personal](/Entregas/Entrega-3/garciaDiego.md)|
|Carlos Alfonso|[Analisis personal](/Entregas/Entrega-3/alfonsoCarlos.md)|
|Iker Celaya|[Analisis personal](/Entregas/Entrega-3/celayaIker.md)|
|Sebastian Chmielowski|[Analisis personal](/Entregas/Entrega-3/chmielowskiSebastian.md)|
|Cesar García|[Analisis personal](/Entregas/Entrega-3/garciaCesar.md)|
|Valvanuz Obregón|[Analisis personal](/Entregas/Entrega-3/obregonValvanuz.md)|
|Eduardo Olea|[Analisis personal](/Entregas/Entrega-3/oleaEduardo.md)|
|Lucia Prieto|[Analisis personal](/Entregas/Entrega-3/prietoLucia.md)|
|Daniel Puente|[Analisis personal](/Entregas/Entrega-3/puenteDaniel.md)|
|Anette Torres|[Analisis personal](/Entregas/Entrega-3/torresAnette.md)|

### Notas para el análisis

- Buscar patrones comunes entre miembros.
- Identificar vulnerabilidades compartidas.
- Detectar puntos ciegos en la gestión de privacidad.
- ***Códigos sugeridos***: 🟢 Bajo riesgo/impacto / 🟡 Riesgo/impacto moderado / 🔴 Alto riesgo/impacto


#### Resumen cuantitativo por miembro

<div align=center>

|Métrica|Diego García|Carlos Alfonso|Iker Celaya|Sebastian Chmielowski|Cesar García|Valvanuz Obregón|Eduardo Olea|Lucia Prieto|Daniel Puente|Anette Torres|Patrón grupal<br>(Media y desviación)|
|-|-|-|-|-|-|-|-|-|-|-|-|
|Índice de exposición global|🟡|🟡|🟡|🟢|🔴|🟢|🟢|🟢|🟡|🟢|🟢 (60%), 🟡 (30%), 🔴 (10%)|
|Nº total de hallazgos|15|7|7|13|7|7|12|7|12|3|9.0 ± 3.8|
|% hallazgos en control total|20%|14.3%|42.9%|23.1%|14.3%|57.1%|41.7%|71.4%|41.7%|100%|42.6% ± 28.1%|
|% hallazgos en control parcial|0%|0%|0%|0%|0%|0%|0%|0%|0%|0%|0%|
|% hallazgos sin control|80%|85.7%|71.4%|76.9%|85.7%|42.9%|58.3%|28.6%|58.3%|0%|58.8% ± 28.1%|

</div>

#### Distribución por plataformas

<div align=center>

|Plataforma|Diego García|Carlos Alfonso|Iker Celaya|Sebastian Chmielowski|Cesar García|Valvanuz Obregón|Eduardo Olea|Lucia Prieto|Daniel Puente|Anette Torres|Total grupo|
|-|-|-|-|-|-|-|-|-|-|-|-|
|Redes Sociales|4|4|6|6|1|3|6|4|6|3|43 (50.6%)|
|Foros/Blogs|3|0|0|0|0|0|2|0|0|0|5 (5.9%)|
|Noticias|2|1|0|1|0|0|0|0|0|0|4 (4.7%)|
|Documentos|0|0|1|0|4|0|3|0|2|0|10 (11.8%)|
|Imágenes|0|0|0|1|0|0|0|1|0|0|2 (2.4%)|
|Otros|6|0|0|5|2|4|1|2|4|0|24 (28.2%)|

</div>

#### Matriz de vulnerabilidades comunes

<div align=center>

|Vulnerabilidad|Diego García|Carlos Alfonso|Iker Celaya|Sebastian Chmielowski|Cesar García|Valvanuz Obregón|Eduardo Olea|Lucia Prieto|Daniel Puente|Anette Torres|% Grupo|Riesgo medio|
|-|-|-|-|-|-|-|-|-|-|-|-|-|
|Datos personales expuestos|2|0|0|0|0|0|0|0|0|3|20%|🟡|
|Información profesional|1|0|0|0|1|0|0|1|0|1|40%|🟢|
|Fotos personales|3|0|1|1|0|3|0|1|0|2|60%|🟡|
|Menciones en medios|0|0|0|0|0|0|0|0|0|0|0%|🟢|
|Documentos académicos|0|0|0|0|1|1|0|0|1|1|40%|🟢|
|Perfiles abandonados|0|2|1|1|0|0|0|0|1|0|50%|🟡|

</div>

#### Análisis de control

<div align=center>

|Tipo de control|Diego García|Carlos Alfonso|Iker Celaya|Sebastian Chmielowski|Cesar García|Valvanuz Obregón|Eduardo Olea|Lucia Prieto|Daniel Puente|Anette Torres|% Grupo|Riesgo promedio|
|-|-|-|-|-|-|-|-|-|-|-|-|-|
|Total|3|1|2|3|1|4|4|5|5|3|34.2%|🟢|
|Parcial|0|0|0|3|0|0|0|0|0|0|3.4%|🟢|
|Nulo|12|6|5|10|6|3|7|2|7|0|62.4%|🔴|

</div>

#### Análisis de brechas de datos (*';--have i been pwned?*)

<div align=center>

|Exposición|Diego García|Carlos Alfonso|Iker Celaya|Sebastian Chmielowski|Cesar García|Valvanuz Obregón|Eduardo Olea|Lucia Prieto|Daniel Puente|Anette Torres|% grupal|
|-|-|-|-|-|-|-|-|-|-|-|-|
|Total brechas|1|0|2|1|0|2|0|0|0|1|70%|
|Datos personales|1|0|1|1|0|0|0|0|0|0|30%|
|Contraseñas|1|0|4|1|0|0|0|0|0|0|30%|
|Emails|1|0|1|1|0|2|0|0|0|1|50%|
|Servicios críticos|0|0|1|0|0|0|0|0|0|0|10%|

</div>

#### Análisis de impacto

<div align=center>

|Categoría de impacto|Diego García|Carlos Alfonso|Iker Celaya|Sebastian Chmielowski|Cesar García|Valvanuz Obregón|Eduardo Olea|Lucia Prieto|Daniel Puente|Anette Torres|Impacto grupal|
|-|-|-|-|-|-|-|-|-|-|-|-|
|Personal|0|0|0|1|0|3|0|4|1|3|40%|
|Profesional|1|0|0|0|1|0|0|1|0|1|40%|
|Académico|0|0|0|0|1|1|0|0|1|1|40%|
|Social|3|0|0|0|3|0|5|0|4|2|50%|

</div>

[INICIO](/README.md)
