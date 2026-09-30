## Para la pregunta 1:

**ClustalW**: Es un programa y algoritmo de alineamiento múltiple de secuencias biológicas que evalúa la similitud entre cadenas de ADN o proteínas mediante alineamientos en pares y la construcción de un árbol guía progresivo; esta fue utilizada en la alineación simultánea de las secuencias de aminoácidos de las cuatro proteínas de la familia Aldehído Oxidasa (LbotAOX1, EsemAOX1, CmedAOX1 y SinfAOX1) para homologar sus posiciones e insertar los vacíos (*gaps*) necesarios.

**MEGA 12 (Molecular Evolutionary Genetics Analysis)**: Es un software especializado de bioinformática diseñado para la visualización, edición de alineamientos múltiples y análisis evolutivo y filogenético de secuencias; esta fue utilizada en la visualización gráfica a color del alineamiento de aminoácidos, la corrección del desfase de la secuencia CmedAOX1 mediante la re-ejecución del alineamiento y la identificación y conteo de las 21 regiones conservadas con más de tres residuos idénticos.

**NCBI CD-Search (Conserved Domain Search)**: Es un servicio web del NCBI que compara una secuencia proteica contra modelos de perfiles de la base de datos de dominios conservados (CDD) para predecir regiones funcionales y estructurales; esta fue utilizada en la caracterización y mapeo de la arquitectura de dominios de la proteína AOX1, permitiendo asociar las posiciones de las regiones conservadas encontradas con los centros de hierro-azufre ($2\text{Fe}-2\text{S}$), el sitio de unión a FAD y el dominio catalítico de molibdopterina (Moco).

**Visual Studio Code (VS Code)**: Es un editor de texto estructurado y entorno de trabajo que permite la inspección, lectura y edición fina de archivos de código y datos en formatos biológicos; esta fue utilizada en la revisión del formato FASTA, la corrección de errores de sintaxis en las secuencias de entrada (como paréntesis e interrupciones) y la lectura directa del consenso en los archivos con extensión `.aln`.

## Para la pregunta 2 (hipoteticamente hablando, ya usted me confirma si esto es valido o no)

**NCBI BLAST (BLASTp)**: Es un algoritmo de búsqueda de alineamiento local que compara una secuencia problema contra bases de datos proteicas para encontrar secuencias homólogas mediante puntuaciones de similitud y valores *e-value*; esta podria ser utilizada en la identificación y selección de secuencias ortólogas de la familia AOX1 en la base de datos de proteínas para evaluar su porcentaje de identidad y cobertura.

**NCBI Protein Database**: Es el repositorio público de secuencias proteicas del NCBI que compila datos de traducción de GenBank, RefSeq y Swiss-Prot; esta pudo/podria ser utilizada en la búsqueda, verificación de números de acceso y descarga de los archivos de secuencia primaria en formato FASTA para cada organismo.

**MEGA 12 (Módulo de Inferencia Filogenética)**: Es un software especializado en bioinformática evolutiva que cuenta con herramientas para el cálculo de distancias genéticas y la reconstrucción de árboles filogenéticos mediante métodos estadísticos; podria haberla usado en la construcción del árbol filogenético (por métodos como *Neighbor-Joining* o *Maximum Likelihood*) a partir del alineamiento múltiple para determinar la relación evolutiva entre las secuencias.

**ClustalW** : Es un algoritmo de alineamiento múltiple progresivo de secuencias biológicas que alinea cadenas de aminoácidos mediante la construcción de una matriz de distancias y un árbol guía; puede ser usada en la homologación de las secuencias recuperadas para preparar la matriz de datos requerida en el análisis filogenético.

**NCBI CD-Search (Conserved Domain Search)**: Es una herramienta del NCBI que compara secuencias de aminoácidos contra modelos de perfiles (PSSM) de la base de datos CDD para identificar bloques funcionales; puede ser usada en la confirmación y delimitación de los dominios $2\text{Fe}-2\text{S}$, FAD y Moco en las secuencias analizadas en la reconstrucción evolutiva.