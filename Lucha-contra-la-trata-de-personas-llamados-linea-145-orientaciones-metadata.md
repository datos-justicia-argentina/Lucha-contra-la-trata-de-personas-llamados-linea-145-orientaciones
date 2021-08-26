Lucha contra la trata de personas - Llamados línea 145 - Orientaciones
----------------------------------------------------------------------

En este conjunto de datos se detallan las orientaciones llevadas a cabo ante comunicaciones recibidas por la Línea 145 en las cuales se describen hechos que no encuentran vinculación con el delito de trata de personas, pero que merecen algún tipo de prestación, ya sea por vincularse con otros delitos, situaciones de extrema vulnerabilidad o requerir articulación con otros organismos.

http://datos.jus.gob.ar/dataset/lucha-contra-la-trata-de-personas-llamados-linea-145-orientaciones

https://www.argentina.gob.ar/jefatura/comitecontralatrata


Características
---------------

-   **Fecha de Primera** **Publicación:** 12/06/2018

-   **Tags o Etiquetas:** 145, trata, explotación, oferta sexual, desapariciones, grooming, captaciones, víctimas, género, vulnerabilidades, orientaciones, conflicto vecinal, adicciones, consumo, abuso infantil, denuncia

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Política Criminal. Programa Nacional de Rescate y Acompañamiento a las Personas Damnificadas por el Delito de Trata

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Política Criminal. Programa Nacional de Rescate y Acompañamiento a las Personas Damnificadas por el Delito de Trata

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Política Criminal. Programa Nacional de Rescate y Acompañamiento a las Personas Damnificadas por el Delito de Trata

-   **Grupo:** Acceso a Justicia

-   **Frecuencia de Actualización:** Mensualmente

> La estructura mencionada a continuación hace referencia a los archivos publicados en el portal datos.jus.gob.ar a partir del mes de enero 2020. Los datos publicados surgen a patir de la registración en el sistema SICAJ (Sistema Informático de los Centros de Acceso a Justicia)

Recursos disponibles
--------------------

### Lucha contra la trata de personas orientaciones línea 145 – 202001 - AAAAMM

-   **Nombre del archivo:** lucha-contra-la-trata-de-personas-llamados-linea-145-orientaciones-202001-AAAAMM.csv

-	**Descripción del contenido:** detalle de las orientaciones efectuadas ante comunicaciones recibidas en la línea 145 relacionadas con hechos no vinculados con el delito de trata, pero si con otros delitos, situaciones de extrema vulnerabilidad o que requieren intervención de otros organismos

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** desde enero de 2020 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **fecha_ingreso (date)**: fecha en que se cargan los datos en el sistema. Las orientaciones son cargadas en el sistema al momento de realizarlas. Formato AAAA-MM-DD

-	**hora_ingreso (datetime)**: hora en que se cargan los datos en el sistema. Formato hh:mm

-   **nro_registro_interno(int):** identificador de la orientación. Permite relacionar a las orientaciones con la tabla de referidos en las orientaciones

-   **situación (string):** refiere a la evaluación que realiza la o el profesional que toma la consulta, según una serie de indicadores, en la cual determina si se trata de una urgencia o una emergencia. Esta evaluación determina el tipo de derivación que se efectúa

-   **origen (string):** indica si la consulta la realizó un ciudadano o una institución

-   **es_anonima (string):** toma valor Sí cuando no se identifica la persona que realiza la denuncia

-   **tema (string):** refiere a la clase de problemática por la cual se realiza la orientación. Puede tomar los siguientes valores, entre otros:

   	-	Abuso sexual infantil
	
	-	Acceso a documentacion personal y certificaciones 
	
	-	Derechos de usuarios/as y consumidores/as
	
	-	Relaciones de familia
	
	-	Salud
	
	-	Trabajo
	
-   **subtema(string):** refiere al subtema de la orientación. Subtemas posibles, entre otros:

	-	Anses	
	
	-	Conflicto vecinal
	
	-	Consumo problemático, adicciones o alcoholismo
		
	–	Violacion de cuarentena
	
-   **provincia(string):** provincia en la que aconteció el hecho referido

-   **localidad(string):** localidad en la que aconteció el hecho referido

-   **barrio (string):** barrio en el que aconteció el hecho referido

-   **dependencia_alta (string):** dependencia que recibió la consulta

-   **via_ingreso(string):** medio a través del cual ingresa la consulta. Puede tomar los valores:

	-	Línea 145
	
	-	Correo institucional
	
	-	Teléfono institucional

-   **consultante_nacionalidad(string):** nacionalidad del consultante
	
-   **consultante_provincia(string):** proviancia en la que se encuentra el consultante

-   **consultante_localidad(string):** localidad en la que se encuentra el consultante
	
-   **consultante_tipo(string):** refiere al tipo de consultante. Puede tomar los valores:

	-	Consultante
	
	-	Denunciante - ciudadano
	
	-	Denunciante - institución

	-	Denunciante - institución
	
	-	Denunciante - víctima directa
	
	-	Denunciante - víctima indirecta
	
	-	Entrevistado
	
-   **consultante_como_conocio_la_linea(string):** refiere al medio por el cual conoció la línea la persona que realiza la consulta
	
-   **consultante_genero(string):** género de la persona que realiza la consulta. Puede tomar los valores:

	-	Hombre

    -   Mujer

    -   Transexual

    -   Transgénero

    -   Travesti
	
-   **consultante_edad_aparente(string):** edad aparente de la persona que realiza la consulta
	
-   **provincia_indec_id(string):** código de provincia desde la cual se requiere orientación, según la codificación de provincia implementada por INDEC (hasta 05/2019 nombre campo orientacion_provincia_indec_id)

### Lucha contra la trata de personas orientaciones 145 – referidos 202001 - AAAAMM

-   **Nombre del archivo:** lucha-contra-la-trata-de-personas-linea-145-orientaciones-referidos-202001-AAAAMM.csv

-	**Descripción del contenido:** detalle de las personas a que se hace referencia en las consultas o solicitudes de orientación recibidas en la línea 145 relacionadas con hechos no vinculados con el delito de trata, pero si con otros delitos, situaciones de extrema vulnerabilidad o que requieren intervención de otros organismos

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** desde enero de 2020 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **nro_registro_interno(int):** identificador de la orientación. Permite relacionar al referido con la orientación

-   **fecha_ingreso_consulta (date)**: fecha en la que se ingresa la consulta al sistema. Formato AAAA-MM-DD

-   **tema(string):** refiere a la problemática por la cual se realiza la consulta. Toma los mismos valores que en la consulta relacionada
 
-   **subtema(string):** refiere al subtema de la orientación. Toma los mismos valores que en la consulta relacionada

-   **referido_tipo(string):** referido tipo. Puede tomar los siguientes valores:

	-	Acusado
	
	-	Víctima directa
	
	-	Víctima indirecta - familiar

-   **nacionalidad(string):** nacionalidad de la persona referida

-   **provincia(string):** provincia a la que pertenece la persona referida

-   **localidad(string):** localidad a la que pertenece la persona referida

-   **genero(string):** género de la persona referida. Puede tomar los mismos valores que el campo consultante_genero

-   **edad_aparente(string):** edad aparente de la persona referida

-   **embarazada(string):** toma valos Sí cuando la persona referida está embarazada

-   **discapacidad(string):** toma valos Sí cuando la persona referida posee algún tipo de discapacidad

-   **provincia_indec_id(string):** código de la provincia a la que pertenece la persona referida, según la codificación de provincia implementada por INDEC

### Lucha contra la trata de personas orientaciones línea 145 – AAAA

-   **Nombre del archivo:** lucha-contra-la-trata-de-personas-orientaciones-linea-145-AAAA.zip

-	**Descripción del contenido:** detalle de las orientaciones efectuadas ante comunicaciones recibidas en la línea 145 relacionadas con hechos no vinculados con el delito de trata en el año AAAA

-   **Formato:** ZIP

### Lucha contra la trata de personas denuncias línea 145 – referidos - AAAA

-   **Nombre del archivo:** oficina-rescate-denuncias-referidos-AAAA.zip

-	**Descripción del contenido:** referidos en las orientaciones recibidas en la Línea 145 sobre trata de personas en el año AAAA

-   **Formato:** ZIP


> La estructura mencionada a continuación hace referencia a los archivos publicados en el portal datos.jus.gob.ar durante el período comprendido entre el año 2017 y 2019 organizados en archivos anuales.


### Campos del recurso

-   **orientacion_fecha (date)**: fecha en que se atendió el llamado. Formato AAAA-MM-DD

-   **orientacion_tema (string)**: refiere a la clase de problemática en la cual se encuadran los hechos  por los cuales la persona se comunica. Puede tomar los siguientes valores:

    -   Acceso a documentación personal y certificados (1)
    -   Actos de gobierno o agentes públicos (2)
    -   Conflictos colectivos de pueblos originarios (3)
    -   Daños y responsabilidad civil (4)
    -   Derechos de usuarios/as y consumidores/as (5)
    -   Deudas (6)
    -   Discriminación (7)
    -   Educación (8)
    -   Justicia Penal (9)
    -   Relaciones de familia (10)
    -   Salud (11)
    -   Seguridad Social (12)
    -   Trabajo (13)
    -   Víctima de delito (14)
    -   Violencia de género(14)
    -   Vivienda (15)
    
-   **orientacion_subtema (string)**: refiere al subtema de la orientación. Subtemas posibles para orientación_tema:

    -    (1): Certificado de antecedentes penales / Certificado de discapacidad / Trámites de migraciones, radicaciones, ciudadanía o refugio / Trámites relativos a personas jurídicas / Trámites relativos a documentación de Identidad o partidas / Trámites relativos a SUBE, pases, certificados o boletos de transporte público / Situación de NN / Otro (Acceso a documentación personal y certificados).
    -    (2): Abuso de autoridad policial / Cuestiones electorales / Cuestiones Tributarias o Impositivas / Exigencias burocráticas desmedidas o irrazonables para trámites / Exigencias ilegales por parte de funcionarios/as / Falta de Acceso a información pública o datos personales / Maltrato en oficinas públicas / Multas, infracciones, clausuras, penalidades, etc. / Negativa a recibir denuncias o trámites / Reclamos Ambientales / Otro (Actos de gobierno o agentes públicos).
    -   (3): Conflictos territoriales / Consulta previa o participación / Falta de adecuación cultural de políticas públicas / Personería Jurídica / Otro (Conflictos colectivos de pueblos originarios).
    -   (4): Accidente de tránsito con vehículo particular / Accidente de tránsito de transporte público / Daños derivados de productos o servicios defectuosos / Daños derivados de eventos naturales / Incumplimientos de contratos / Otro tipo de accidentes / Otro (Daños y responsabilidad civil).
    -   (5): Empresas de telecomunicación / Empresas de seguros / Productos defectuosos / Servicios de profesionales deficientes o excesivamente onerosos / Servicios bancarios, de financieras o prestamistas / Tarjetas de crédito / Transporte público / Otro (Derechos de usuarios/as y consumidores/as).
    -   (6): Acción por parte de acreedores/as / Calificaciones de riesgo crediticio / Cobro de deuda / Concursos o Quiebras / Obtención de préstamo o inversión propia / Otro (Deudas).
    -   (7): Por discapacidad / Por edad / Por lugar de residencia / Por orientación sexual o identidad de género / Por nacionalidad o pertenencia a un Pueblo Indígena / Por religión / Por rasgos o características físicas / Por situación socio económica / Otro (Discriminación).
    -   (8): Bullying, acoso o agresiones / Falta o negativa de vacantes / Problemas con inscripciones, matrículas o cuotas; becas o programas de formación / Servicios comunitarios o de ONGs / Situación edilicia deficiente / Suspensión o exclusión de una institución escolar / Otro (Educación).
    -   (9): Agravamiento en las formas o condiciones de detención / Ejecución de la pena / Irregularidades en un proceso penal / Problemas con el/la Defensor/a Público/a / Situación de personas investigadas, imputadas o procesadas penalmente / Otro (Justicia Penal).
    -   (10): Adopción / Divorcio y cese de convivencia / Familiar con consumo problemático, adicciones o alcoholismo / Filiación o reconocimiento / Deberes de responsabilidad parental o familiar / Problemas económicos entre miembros de la familia / Protección de niños, niñas y adolescentes en desamparo / Tenencia de hijos/as, régimen de visitas o custodia legal / Testamentos sucesiones y trámites relativos al fallecimiento de una persona / Violencia intrafamiliar / Otro (Relaciones de familia).
    -   (11): Acceso a medicamentos, elementos ortopédicos, insumos, sillas de ruedas / Acceso a servicios públicos de salud / Consumo problemático, adicciones o alcoholismo / Mala praxis o maltrato médico / PAMI / Problema con obra social o empresa de medicina prepaga / Problemas de Alimentación / Salud mental / Otro (Salud).
    -   (12): Acceso a prestaciones sociales de emergencia o ante situaciones críticas / Jubilaciones / Pensiones contributivas y no contributivas / Programas sociales / Servicios comunitarios y sociales de ONGs / Vacantes en comedores comunitarios / Otro (Seguridad Social).
    -   (13): Accidentes o enfermedades de trabajo / Cuestiones salariales o de registración / Cuestiones Sindicales / Denegación de licencias / Despidos / Malas condiciones de trabajo, incluida la inseguridad, salubridad o problemas de medio ambiente / Maltrato, discriminación, falta de respeto, acoso, hostigamiento o mobbing / Programas de capacitación, asistencia a micro-emprendimientos, pymes, etc. Cooperativismo y Economía social / Sanciones o procesos disciplinarios / Situación de desempleo / Otro (Trabajo).
    -   (14): Amenazas / Delitos contra la autonomía o integridad sexual / Delitos contra la integridad física / Delitos contra la libertad, sustracción de identidad o posible desaparición de persona / Delitos contra la propiedad / Explotación sexual / Fraude o estafa / Trata de personas / Otro (Víctima de delito).
    -   (15): Económica / Física / Psicológica / Sexual / Simbólica.
    -   (16): Acceso a vivienda propia / Autorizaciones o permisos de edificación o reformas de  vivienda / Daños contra la propiedad / Desalojo u ocupación de vivienda / Disputas vecinales o con la administración del consorcio / Infraestructura y servicios públicos / Malas condiciones habitacionales / Problemas de alquiler / Problemas con títulos de propiedad, operaciones de compra venta, usufructos / Situación de calle actual o inminente, acceso a paradores u hogares de transitorios, etc. / Otro (Vivienda).

-   **orientacion_seguimiento (string):** registra si es procedente o no dar intervención al área de seguimiento

-   **orientacion_provincia (string):** provincia desde la cual se requiere orientación

-   **orientacion_provincia_id (string):** código de provincia desde la cual se requiere orientación, según la codificación de provincia implementada por INDEC (hasta 05/2019 nombre campo orientacion_provincia_indec_id)

### Notas

[Ley 27.275 - Derecho de Acceso a la Información Pública]( http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

Este Conjunto de datos es publicado en el Portal de Datos Abiertos de la Justicia Argentina mediante [Resolución Nº 187 del Ministerio de Justicia y Derechos Humanos](http://datos.jus.gob.ar/resoluciones/RESOL-2018-187-APN-MJ.pdf), del 9 de Marzo de 2018.
