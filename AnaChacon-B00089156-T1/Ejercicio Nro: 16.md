# Ejercicio Nro: 16

## Enunciado
Objetivo:
Utilizar el método Delphi para llegar a un consenso sobre la tecnologia y la arquitectura más adecuadas para el desarrollo de una billetera virtual segura, escalable y confiable
Descripción:
El método Delphi es una técnica de consulta estructurada que se utiliza para obtener opiniones expertas sobre un tema complejo. En este caso, el método Delphi se utilizará para recopilar información y opiniones de expertos en bloclchain, seguridad, desarrollo de software y arquitectura de sistema sobre la mejor tecnología y arquitectura para una billetera virtual

1. Definición del problema:
    a) Describir claramente los objetivos y requisitos de la billetera virtual, tal como se presento en el enunciado anterior.
    b) Identificar los factores clase que se debenn considerar al seleccionar la tecnologia y la arquitectura, como la seguridad, la escabilidad, la confiabilidad, la facilidad de uso y el costo.
2. Seleccion del plantel de expertos:
    a) Identificar y reclutar a un grupo de expertos con experiencia en las áreas relevantes, como blockchain, seguridad, desarrollo de software y arquitectura de sistemas.
    b) El panel de expertos debe estar compuesto por individuoas con diferentes perspectivas y experiencias para garantizar la diversisas de opiniones 
    c) Es importante que los expertos sean independientes y no tengan conflicos de intereses
3. Elaboración del cuestionario:
    a) Diseñar un cuestionario que presente a los expertos una lista de opciones de tecnología y arquitectura para la billetera virtual
    b) El cuestionario debe incluir preguntas que permitan a los expertos evaluar cada opcion en función de los factores claves identificados en el paso 1
    c) Las preguntas pueden ser de tipo Likert, abiertas o una combinación de ambas.
4. Aplicaciones de método Delphi:
    a) Distribuir el cuestionario a los expertos de forma anónima.
    b) Recopilar las respuestas de los expertos y analizarlas estadisticamente.
    c) Sintetizar los resultados y presentarlos al panel de expertos.
    d) Brindar a los expertos la oportunidad de revisar y comentar los resultados
    e) Realizar una segunda ronda de cuesionarios, incorporando los comentarios de la primera ronda.
    f) Analizar nuevamente las respuestas y presentar los resultados dinales al panel de expertos.
5. Selección de la tecnología y la arquitectura:
    a) Con base en los resultados del método Delphi, seleccionar la tecnología y la arquitectura que mejor se adapten a los objetivos y requisitos de la billetera virtual.
    b) Justificar la seleccion de la tecnología y la arquitectura elegidas, cosiderando los aportes del panel de expertos y los resultados del análisis estadistico.
6. Documentación y comunicación:
    a) Documentar cuidadosamente el proceso de toma de decisiones, incluyendo los criterios utilizados, las opciones consideradas y la justificación de la selección final.
    b) Comunicar la decisioón tomada a las partes interesadas, incluyendo a los desarrolladores, inversores y usuarios potenciales


## Resoluciom
1. Definición del problema:
    A) El objetivo principal es diseñar y definir la infraestructura tecnológica y la estructura de componentes (arquitectura) óptima para poner en marcha una billetera virtual.
    Requisitos del sistema: Debe ser un ecosistema digital capaz de procesar transacciones financieras (envíos de dinero, pagos, cobros, almacenamiento de activos digitales o fiat) garantizando la inmutabilidad de los datos, la alta disponibilidad del servicio y la protección absoluta de los activos y datos personales de los usuarios.
    B) Para evaluar las tecnologías y arquitecturas candidatas, se establecen cinco variables fundamentales:
    Seguridad: Resistencia a ciberataques, encriptación de datos en tránsito y en reposo, autenticación multifactor y cumplimiento de normativas financieras.
    Escalabilidad: Capacidad del sistema para manejar un incremento exponencial de usuarios y picos de transacciones simultáneas sin degradar el rendimiento.
    Confiabilidad: Tolerancia a fallos y alta disponibilidad.
    Facilidad de uso: Viabilidad técnica para que el equipo de desarrollo cree interfaces fluidas.
    Costo: Presupuesto de infraestructura en la nube, licencias de software, costos por transacción (si se usa blockchain) y salarios del equipo técnico especializado en el tiempo de desarrollo previsto.

2. Selección del plantel de expertos
    a) y b) 5 Expertos en Blockchain y Criptografía: Evalúan la viabilidad de usar libros contables distribuidos (DLT), redes públicas (Ethereum/Solana) o permisionadas (Hyperledger) para la transparencia y seguridad transaccional.
    5 Especialistas en Ciberseguridad Financiera: Profesionales con experiencia en auditorías bancarias, pasarelas de pago y mitigación de fraudes.
    5 Arquitectos de Sistemas / Ingenieros de Software Senior: Especialistas en sistemas distribuidos, patrones de arquitectura de software y gestión de infraestructuras en la nube.
    5 Directores de Producto / Product Owners de la industria Fintech: Aportan la visión del mercado, el enfoque de cara al usuario (facilidad de uso) y la viabilidad económica (costos).
    c) Filtro de reclutamiento: Se exige la firma de una declaración jurada de no conflicto de intereses. Ningún experto puede ser empleado directo ni accionista de las empresas proveedoras de las tecnologías de infraestructura específicas que se van a votar, garantizando votos puramente técnicos y neutrales.

3. Elaboración del cuestionario
   A), B) y C) 
    Bloque Tecnológico 1: Arquitectura de Base de Datos y Ledger
        Opción A: Base de datos relacional tradicional (PostgreSQL/Oracle) replicada en la nube.
        Opción B: Ledger Centralizado en la nube (Amazon QLDB) con historial inmutable.
        Opción C: Red Blockchain Permisionada / Privada (Hyperledger Fabric).
        Pregunta: Califique cada opción del 1 al 5 respecto a su Seguridad, Escalabilidad y Costo.
        Pregunta: Si calificó la opción de Blockchain (Opción C) con un puntaje bajo en "Costo" o "Escalabilidad", detalle técnicamente sus motivos.    
    Bloque Tecnológico 2: Arquitectura del Sistema
        Opción X: Arquitectura Monolítica Modular.
        Opción Y: Arquitectura de Microservicios distribuidos mediante contenedores (Docker/Kubernetes).
        Pregunta: Califique cada opción del 1 al 5 respecto a su Confiabilidad y Facilidad de uso.

4. Aplicación del método Delphi
    A) El cuestionario se envía digitalmente a través de una plataforma parametrizada por el mediador. Las identidades de los 20 expertos están codificadas. Ningún participante sabe quiénes son los demás ni qué responde cada uno.
    B) Al cerrar la Ronda 1, el mediador tabula las respuestas cuantitativas y calcula la mediana y el rango intercuartílico.
    Resultados Cuantitativos R1: Las opciones de Bases de Datos     Relacionales (Opción A) y Ledger en la nube (Opción B) muestran una alta concentración de votos positivos en costos y facilidad de uso. La opción Blockchain (Opción C) muestra alta dispersión: excelente seguridad pero bajas calificaciones en escalabilidad por parte de los Arquitectos de Software.
    Resultados Cualitativos R1: Los arquitectos señalan que una blockchain pública ralentizaría los tiempos de respuesta de la app para el usuario común.
    C) y D) El mediador redacta un informe anónimo con los gráficos estadísticos y resúmenes de los argumentos cualitativos. Este informe se distribuye de vuelta a los 20 expertos para su revisión.
    E) Se lanza la Ronda 2. Se les presenta nuevamente el cuestionario, pero esta vez con la información de lo que votó el grupo.
    Pregunta de reevaluación: "La mediana del grupo indica que la opción de Blockchain Privada (Hyperledger) es óptima para la seguridad pero compleja para la facilidad de uso. Sabiendo esto, ¿desea mantener su voto inicial o modificarlo? Si mantiene una postura alejada de la mediana, justifique brevemente su argumento técnico".
    F) El mediador procesa las respuestas de la Ronda 2. Las opiniones muestran convergencia (el rango intercuartílico se reduce drásticamente, lo que indica que se ha alcanzado el consenso técnico). Las respuestas se han estabilizado.

5. Selección de la tecnología y la arquitectura
    A) Con base en el consenso unánime del panel tras la Ronda 2, se selecciona la siguiente combinación:
    Arquitectura de Software: Microservicios distribuidos gestionados con Kubernetes en la nube.
    Tecnología de Datos: Enfoque híbrido compuesto por una Base de Datos Relacional (PostgreSQL) para operaciones rápidas del día a día de la app (UI/UX) y un Ledger Inmutable dedicado exclusivamente a la auditoría y validación de transferencias de fondos críticas.
    B) La selección se justifica analizando las métricas finales del método:
    Seguridad y Confiabilidad (Mediana: 4.8/5): Los expertos en ciberseguridad y blockchain consensuaron que separar la base de datos transaccional del libro de auditoría inmutable protege a la billetera contra manipulaciones internas de saldos y hackeos externos.
    Escalabilidad y Facilidad de uso (Mediana: 4.6/5): Los arquitectos de software coincidieron en que la arquitectura de microservicios permite que la aplicación escale de forma automática ante la demanda de los usuarios, resolviendo el problema de latencia que causaba una red blockchain pura.
    Costo (Mediana: 4.2/5): Los Product Owners determinaron que, si bien una infraestructura híbrida tiene costos iniciales moderados, previene las pérdidas millonarias por caídas del sistema o fraudes, haciendo que la inversión sea altamente rentable a mediano plazo.
6.  Documentación y comunicación
    A) Se genera un Libro Blanco Técnico del Proyecto, custodiado por el grupo de control, que incluye:
    La metodología Delphi empleada, las fechas de las rondas y las métricas de dispersión estadística de cada etapa.
    La matriz completa de tecnologías evaluadas.
    Las minutas anónimas con los argumentos que llevaron a cambiar las posturas hacia el consenso final.
    B) Para asegurar que la decisión sea comprendida y adoptada de forma efectiva por los diferentes actores, se segmenta la comunicación:
    A los Desarrolladores (Equipo Técnico): Se les entrega la documentación de arquitectura detallada, diagramas de componentes y el stack de tecnologías aprobado para que inicien el diseño del código base inmediatamente.
    A los Inversores / Dirección General: Se les presenta un informe ejecutivo financiero donde se explica cómo la tecnología elegida mitiga los riesgos de fraude (seguridad) y cómo se optimizó el presupuesto (costo) gracias al consenso de expertos internacionales.
    A los Usuarios Potenciales (Mercado): Se publica una sección en la web oficial y campañas de marketing destacando la robustez de la plataforma: "Desarrollada bajo los máximos estándares de seguridad y tecnología del mercado validados por expertos de la industria", generando confianza y tracción inicial.
