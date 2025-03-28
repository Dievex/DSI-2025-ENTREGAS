| [![](https://img.shields.io/badge/-Inicio-FFF?style=flat&logo=Emlakjet&logoColor=black)](/README.md) [![](https://img.shields.io/badge/-Entrega_2-FFF?style=flat&logo=openstreetmap&logoColor=black)](/Entregas/Entrega-2/ModeloDeNegocio.md)  [![](https://img.shields.io/badge/-Entrega_3-FFF?style=flat&logo=openstreetmap&logoColor=black)](/Entregas/Entrega-3/DocumentoAnalisis.md)  [![](https://img.shields.io/badge/-Entrega_4-FFF?style=flat&logo=openstreetmap&logoColor=black)]()|
|:-:|
# Analisis Grupal
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

|Métrica|Patrón grupal<br>(Media y desviación)|Miembro 1|Miembro 2|Miembro 3|Miembro 4|Miembro 5|Miembro 6|Miembro 7|Miembro 8|Miembro 9|Miembro 10|
|-|-|-|-|-|-|-|-|-|-|-|-|
|Índice de exposición global|🟡|🟡|🟡|🟢|🔴|🟢|🟢|🟢|🟡|🟢|🟢 (50%), 🟡 (40%), 🔴 (10%)|
|Nº total de hallazgos|15|7|7|13|7|7|12|7|12|3|9.0 ± 3.8|
|% hallazgos en control total|20%|14.3%|42.9%|23.1%|14.3%|57.1%|41.7%|71.4%|41.7%|100%|42.6% ± 28.1%|
|% hallazgos en control parcial|0%|0%|0%|0%|0%|0%|0%|0%|0%|0%|0%|
|% hallazgos sin control|58.8% ± 28.1%|80%|85.7%|71.4%|76.9%|85.7%|42.9%|58.3%|28.6%|58.3%|0%|

</div>

#### Distribución por plataformas

<div align=center>

|Plataforma|Total grupo|Miembro 1|Miembro 2|Miembro 3|Miembro 4|Miembro 5|Miembro 6|Miembro 7|Miembro 8|Miembro 9|Miembro 10|
|-|-|-|-|-|-|-|-|-|-|-|-|
|Redes Sociales|43 (50.6%)|4|4|6|6|1|3|6|4|6|3|
|Foros/Blogs|5 (5.9%)|3|0|0|0|0|0|2|0|0|0|
|Noticias|4 (4.7%)|2|1|0|1|0|0|0|0|0|0|
|Documentos|10 (11.8%)|0|0|1|0|4|0|3|0|2|0|
|Imágenes|2 (2.4%)|0|0|0|1|0|0|0|1|0|0|
|Otros|24 (28.2%)|6|0|0|5|2|4|1|2|4|0|

</div>

#### Matriz de vulnerabilidades comunes

<div align=center>

|Vulnerabilidad|% Grupo|Riesgo medio|Miembro 1|Miembro 2|Miembro 3|Miembro 4|Miembro 5|Miembro 6|Miembro 7|Miembro 8|Miembro 9|Miembro 10|
|-|-|-|-|-|-|-|-|-|-|-|-|-|
|Datos personales expuestos|20%|🟡|2|0|0|0|0|0|0|0|0|3|
|Información profesional|40%|🟢|1|0|0|0|1|0|0|1|0|1|
|Fotos personales|60%|🟡|3|0|1|1|0|3|0|1|0|2|
|Menciones en medios|0%|🟢|0|0|0|0|0|0|0|0|0|0|
|Documentos académicos|40%|🟢|0|0|0|0|1|1|0|0|1|1|
|Perfiles abandonados|50%|🟡|0|2|1|1|0|0|0|0|1|0|

</div>

#### Análisis de control

<div align=center>

|Tipo de control|% Grupo|Riesgo promedio|Miembro 1|Miembro 2|Miembro 3|Miembro 4|Miembro 5|Miembro 6|Miembro 7|Miembro 8|Miembro 9|Miembro 10|
|-|-|-|-|-|-|-|-|-|-|-|-|-|
|Total|34.2%|🟢|3|1|2|3|1|4|4|5|5|3|
|Parcial|3.4%|🟢|0|0|0|3|0|0|0|0|0|0|
|Nulo|62.4%|🔴|12|6|5|10|6|3|7|2|7|0|

</div>

#### Análisis de brechas de datos (*';--have i been pwned?*)

<div align=center>

|Exposición|% grupal|Miembro 1|Miembro 2|Miembro 3|Miembro 4|Miembro 5|Miembro 6|Miembro 7|Miembro 8|Miembro 9|Miembro 10|
|-|-|-|-|-|-|-|-|-|-|-|-|
|Total brechas|70%|1|0|2|1|0|2|0|0|0|1|
|Datos personales|30%|1|0|1|1|0|0|0|0|0|0|
|Contraseñas|30%|1|0|4|1|0|0|0|0|0|0|
|Emails|50%|1|0|1|1|0|2|0|0|0|1|
|Servicios críticos|10%|0|0|1|0|0|0|0|0|0|0|

</div>

#### Análisis de impacto

<div align=center>

|Categoría de impacto|Impacto grupal|Miembro 1|Miembro 2|Miembro 3|Miembro 4|Miembro 5|Miembro 6|Miembro 7|Miembro 8|Miembro 9|Miembro 10|
|-|-|-|-|-|-|-|-|-|-|-|-|
|Personal|40%|0|0|0|1|0|3|0|4|1|3|
|Profesional|40%|1|0|0|0|1|0|0|1|0|1|
|Académico|40%|0|0|0|0|1|1|0|0|1|1|
|Social|50%|3|0|0|0|3|0|5|0|4|2|

</div>

[INICIO](/README.md)
