# Introducci&oacute;n a la gen&oacute;mica evolutiva - LEG/UM5

## Ediciones del Curso

1a. Edición: [EG1-LEG/UM5](http://www.fsr.ac.ma/content/g%C3%A9nomique) en la Faculté des Sciences Rabat, 10-14 Junio, 2019.

<!-- <img src="docs/pics/Participantes_curso_intro2phyloinfo_UNLP_2-6Julio2018.jpg" /> -->


***
 
## Presentaci&oacute;n

### El profesor
Hola, me llamo [Pablo Vinuesa](http://www.ccg.unam.mx/~vinuesa/). Soy investigador titular del 
[Centro de Ciencias Gen&oacute;micas](http://www.ccg.unam.mx) de la 
[Universidad Nacional Aut&oacute;noma de M&eacute;xico - UNAM](http://www.unam.mx/).

Mis [l&iacute;neas de investigaci&oacute;n](http://www.ccg.unam.mx/~vinuesa/research.html) 
integran la gen&oacute;mica y la bioinform&aacute;tica con la biolog&aacute;a y gen&eacute;tica molecular para entender 
la evoluci&oacute;n y emergencia de pat&oacute;genos oportunistas a partir de microbios ambientales.

### Sobre el material did&aacute;ctico
A trav&eacute;s de estas p&aacute;ginas se distribuyen los apuntes, ejercicios y datos que se usar&aacute;n en el Taller.
Es una recopilaci&oacute; de material desarrollado por [Pablo Vinuesa](http://www.ccg.unam.mx/~vinuesa/), instructor del Taller, 
para diversos cursos y talleres que ha impartido principalmente en la [Universidad Nacional Aut&oacute;noma de M&eacute;xico - UNAM](https://www.unam.mx/). 
Este matrial docente lo distribuyo p&uacute;blicamente a trav&eacute;s de este repositorio GitHub bajo la licencia de Creative Commons.


### Licencia y t&eacute;rminos de uso
Este material docente del curso [**GE1-LEG-UM5**](https://github.com/vinuesa/intro2phyloinfo) lo distribuyo p&uacute;blicamente a trav&eacute;s de este [repositorio GitHub](https://github.com/vinuesa/intro2phyloinfo) bajo la [**Licencia No Comercial Creative Commons 4.0**](https://creativecommons.org/licenses/by-nc/4.0/) 

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 

#### Clonaci&oacute;n del repositorio
Si tienes instalado [git](https://git-scm.com/) en tu computadora, puedes clonar el repositorio con el comando:

   <code>git clone https://github.com/vinuesa/Evolutionary_Genomics1-LEG-UM5.git</code>

En [ubuntu](https://www.ubuntu.com/) es muy f&aacute;cil instalar git: 

  <code>sudo apt install git</code>



<!--
### ¿Horario y lugar de impartici&oacute;n de las sesiones?
Las clases se imparten en el sal&oacute;n de c&oacute;mputo del Instituto de Biotecnolog&iacute;a 
de 9 a 18 hrs. Algunas sesines te&oacute;ricas esperamos poder impartirlas en el auditorio.


<img src="docs/pics/intro2phyloinfo_aula_UNLP_2-6Julio2018.jpg" />

-->

### Objetivos, estructura y resumen de contenidos del Taller
Cada tema tiene un bloque de teor&iacute;a y una o m&aacute;s sesiones pr&aacute;cticas asociadas. Se explicar&aacute;n los principios b&aacute;sicos de b&uacute;squeda de hom&oacute;logos en bases de datos, alineamientos m&uacute;ltiples, e inferencia filogen&eacute;tica, para culminar con el an&aacute;lisis pangen&oacute;mico y filogen&oacute;mico de genomas microbianos.

#### Lunes 2. 
- Introducción a Linux (teoría y práctica)
- Conceptos básicos de biología evolutiva y filogenética

#### Martes 3. 
- Búsqueda de homólogos usando BLAST desde la línea de comandos (prácticas)
- Alineamientos múltiples (prácticas)
- Introducción a los métodos filogenéticos, árboles de genes y de árboles de especies

#### Miércoles 4. 
- Modelos de sustitución y máxima verosimilitud (teoría)
- Ajuste de modelos e inferencia de filogenias de máxima verosimilitud (prácticas)
- Delimitación de especies bacterianas usando métodos evolutivos y datos multilocus

#### Jueves 5. 
- Inferencia bayesiana de filogenias (teoría y práctica)
- Pangenómica y evolución microbiana (Seminario de investigación)

#### Viernes 6.
- Cómputo de familias de genes homólogos con datos genómicos (teoría)
- Análisis pangenómico usando GET_HOMOLOGUES (prácticas)
- Estrategias para la estima de filogenias genómicas (teoría)
- Estima de filogenias genómicas con GET_PHYLOMARKERS (prácticas)


### Software:

- [GET_HOMOLOGUES](http://eead-csic-compbio)
- [GET_PHYLOMARKERS](https://github.com/vinuesa/)
- [Seaview (visor-editor de alineamientos y más)](http://pbil.univ-lyon1.fr/)
- [jModelTest2](https://github.com/ddarriba/)
- [FigTree (para visualizar y editar árboles)](http://tree.bio.ed.ac.uk/)
- [MrBayes](http://mrbayes.sourceforge)

## Temario detallado y material asociado

<!--

2. Gen&oacute;mica comparativa y pan-gen&oacute;mica [presentaci&oacute;n - PDF](https://github.com/vinuesa/intro2phyloinfo/tree/master/docs/introduccion_a_la_pangenomica_microbiana_OMICAS-UAEM_Mar18.pdf)
 + pr?cticas con [GET_HOMOLOGUES](https://github.com/eead-csic-compbio/get_homologues) [tutorial html](http://eead-csic-compbio.github.io/get_homologues/manual/manual.html)
3. Filogen&oacute;mica y estructura filogen?tica del pan-genoma
 +  pr?cticas con [GET_PHYLOMARKERS](https://github.com/vinuesa/get_phylomarkers)

Desde este sitio se distribuyen los materiales did&aacute;cticos bajo la [licencia de
Creative Commons](https://creativecommons.org/).

-->

### Tema 0: Introducci&oacute;n al bioc&oacute;mputo en sistemas GNU/Linux (2-07-2018)

El trabajo en gen&oacute;mica se realiza en servidores UNIX o GNU/Linux de alto rendimiento. Es por ello 
esencial familiarizarse con este ambiente de c&oacute;mputo al inicio de la formaci&oacute;n acad&eacute;mica. 
En consecuencia:

- todas las pr&aacute;cticas asociadas a este Taller se realizan en m&aacute;quinas GNU/Linux
- iniciamos el Taller aprendiendo un poco de Linux. 

#### Introducci&oacute;n al bioc&oacute;mputo en sistemas GNU/Linux 
- [presentaci&oacute;n - PDF](https://vinuesa.github.io/intro2phyloinfo/Intro2biocomputo_sistemas_en_sistemas_UNIX-Linux.pdf)

#### Pr&aacute;ctica 1. Primer contacto con un sistema GNU/Linux
- [pr&aacute;ctica1 - html](https://vinuesa.github.io/intro2phyloinfo/intro2linux/)
- [pr&aacute;ctica1 - pdf](https://vinuesa.github.io/intro2phyloinfo/intro2linux/working_with_linux_commands.pdf)
- [pr&aacute;ctica1 - tabla_comandos](https://vinuesa.github.io/intro2phyloinfo/intro2linux/linux_commands.tab)


#### Pr&aacute;ctica 2. Descarga de secuencias en formato FASTA de GenBank usando el sistema ENTREZ y parseo de los archivos usando herrramientas de filtrado
- [pr&aacute;ctica2 - html](https://vinuesa.github.io/intro2phyloinfo/practica2_parseo_fastas/)
- [pr&aacute;ctica2 - pdf](https://vinuesa.github.io/intro2phyloinfo/practica2_parseo_fastas/ejercicio_parseo_fastas_ENTREZ.pdf)
- [pr&aacute;ctica2 - fasta](https://vinuesa.github.io/intro2phyloinfo/practica2_parseo_fastas/data/recA_Bradyrhizobium_vinuesa.fa)

### Tema 1: Conceptos básicos de evolución
- [presentación - pdf](https://vinuesa.github.io/intro2phyloinfo/tema1_conceptos_basicos_evolucion/Teoria1_conceptos_básicos_de_filoinformática_y_diversidad_microbiana.pdf)

### Tema 2: Búsqueda de homólogos mediante BLAST: teoría y práctica
- [presentación - pdf](https://vinuesa.github.io/intro2phyloinfo/tema2_BLAST/Tema2_BLAST_OVERVIEW.pdf)
- [pr&aacute;ctica1 - comandos](https://vinuesa.github.io/intro2phyloinfo/tema2_BLAST/data/running_and_parsing_BLAST_from_the_cmmd_line.commands)
- [pr&aacute;ctica1 - 16S_4blastN.tgz ](https://vinuesa.github.io/intro2phyloinfo/tema2_BLAST/data/16S_4blastN.tgz)
- [pr&aacute;ctica1 - gene_discovery_and_annotation_using_blastx.tgz](https://vinuesa.github.io/intro2phyloinfo/tema2_BLAST/data/gene_discovery_and_annotation_using_blastx.tgz)

### Tema 3: Alineamientos múltiples: teoría y práctica
- [presentación - pdf](https://vinuesa.github.io/intro2phyloinfo/tema3_alineamientos_multiples/Tema3_alineamientos_multiples.pdf)
- [pr&aacute;ctica1 - tgz](https://vinuesa.github.io/intro2phyloinfo/tema3_alineamientos_multiples/data/practicas_aln_multiples.tgz)


### Tema 4: Introducción a los métodos filogenéticos y modelado paramétrico de evolución de secuencias nucleotídicas: teoría y práctica
- [presentación - pdf](https://vinuesa.github.io/intro2phyloinfo/tema4_modelos_y_maxima_verosimilitud/Tema4_intro_a_la_filogenetica_y_modelos_de_sustitucion.pdf)

### Tema 5: Máxima verosimilitud: estima de parámetros y selección de models - teoría y práctica
- [presentación - pdf](https://vinuesa.github.io/intro2phyloinfo/tema4_modelos_y_maxima_verosimilitud/Tema5_maxima_verosimilitud_y_seleccion_de_modelos.pdf)
- [pr&aacute;ctica1 - tgz](https://vinuesa.github.io/intro2phyloinfo/tema4_modelos_y_maxima_verosimilitud/data/practicas_MV_y_seleccion_modelos.tgz)


### Tema 6: Introducción a la pangenómica microbiana con [GET_HOMOLOGUES](https://github.com/eead-csic-compbio/get_homologues) - teoría y práctica
- [presentación - pdf](https://vinuesa.github.io/intro2phyloinfo/tema5_get_hom_get_phy/introduccion_a_la_pangenomica_microbiana_UNLP_5Jul18.pdf)
- [pr&aacute;ctica1 - tgz](https://vinuesa.github.io/intro2phyloinfo/tema5_get_hom_get_phy/data/get_hom.tgz)
- [tutorial - GET_HOMOLOGUES/GET_PHYLOMARKERS - docker](https://vinuesa.github.io/get_phylomarkers/#get_phylomarkers-tutorial)
- [start_docker - script](https://vinuesa.github.io/intro2phyloinfo/tema5_get_hom_get_phy/data/start_docker.sh)

### Tema 7: Introducción a la filogenómica microbiana con [GET_PHYLOMARKERS](https://github.com/vinuesa/get_phylomarkers) - teoría y práctica
- [presentación - pdf](https://vinuesa.github.io/intro2phyloinfo/tema5_get_hom_get_phy/introduccion_a_la_filogenomica_microbiana_UNLP_5Jul18.pdf)
- [paper GET_PHYLO - pdf](https://vinuesa.github.io/intro2phyloinfo/tema5_get_hom_get_phy/data/get_phylo/Vinuesa_GET_PHYLOMARKERS_FrontMicro2018.pdf)
- [manual - GET_PHYLOMARKERS](https://vinuesa.github.io/get_phylomarkers/#get_phylomarkers-manual)
- [tutorial - GET_PHYLOMARKERS](https://vinuesa.github.io/get_phylomarkers/#get_phylomarkers-tutorial)


### Tema 8: Inferencia bayesiana de filogenias con [MrBayes](http://mrbayes.sourceforge.net/index.php) - teoría y práctica
- [presentación - pdf](https://vinuesa.github.io/intro2phyloinfo/tema6_inferencia_bayesiana/inferencia_bayesiana_con_MrBayes.pdf)
- [pr&aacute;ctica1 - tgz](https://vinuesa.github.io/intro2phyloinfo/tema6_inferencia_bayesiana/data/MrBayes.tgz)


<!--


#### Pr&aacute;ctica 3. Introducci&oacute;n a la inferencia filogen&oacute;mica usando GET_PHYLOMARKERS
- [pr&aacute;ctica1 - html](https://vinuesa.github.io/get_phylomarkers/)

-->
