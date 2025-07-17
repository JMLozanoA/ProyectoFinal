#Sistem�tica filogenética de las ranas Pristimantis del grupo rubicundus, incluyendo dos secuencias novedosas (no publicadas)
#de poblaciones al norte de Colombia que presentan características morfológicas distintas y podrían representar una nueva especie dentro  clado.


#En este estudio se plantea hipotetizar las relaciones filogenéticas del grupo de ranas P. rubicundus y determinar la posición filogenética de una posible nueva entidad
#al norte de Colombia con el uso del marcador molecular 16S.

#El muestreo consistió en todas las secuencias del marcador 16S disponibles en el NCBI para las especies del grupo rubicundus, las cuales son
#Pristimantis labiosus, P. crenunguis y P. chocoensis. Se incluyeron también dos secuencias novedosas (no publicadas) de la población de interés
#al norte de COlombia (Carmen de Atrato, Chocó). Adicionalmente se incluyeron secuencias de las epsecies P. actites  y P. lathanithes como grupo
#externo y raíz del árbol.

#Los programas utilizados fueron muscle para el alineamiento y iqtree2 para recrear la hipótesis flogenética

#Para correr el script devberás hacer lo siguiente:

#El primer pas será correr el programa llamado NCBI con 
	
	bash NCBI
#Este descargará todas las secuencias de 16S disponibles en el NCBI correspondientes a las especies de interés.

#Posteriormente, deberás descargar las secuencias (archivo txt) anexados al repositorio Git Hub (son secuencias no publicadas)

#Una vez descargadas las secuencias nuevas y subidas al supercomputador Hoffman, se deberá navegar hacia la capeta llamada "Fasta" que se acaba de crear producto del
#paso anterior.

#Una vez en la carpeta solo se deberán correr los programas en este orden

# 1. Concatenate 2. Alignment 3. ALignmentNames 4. IQTREE

#Esto generará como resultado unn árbol filogenético apto para abrir en FigTree

#Finalmente, se deberá descargar el árbol  abrir en FigTree par su análisis.

#Discusión y Conclusiones

#El árbo de gen (16S) recopilado demuestra, primeramente, que Pristimantis labiosus representa en realidad un grupo parafilético, conformado por cuatro linao
#linajes independientes (rosado, verde, cian, azul). Por otra parte, Pristimantis crnunguis corresponde a un grupo monofilético, y la secuencia que se anida con
#el grupo rosado de P. labiosus corresponde probablemente a un individuo mal identificado que no es P. crenunguis. Finalmente, las secuencias nuevas han conformado
#un linaje genéticamente distinto a las demás especies del grupo, ubicandose como grupo hermano de P. labiosus grupo azul. Esto quiere decir, que al menos en el gen
#mitocondrial 16S existen diferencias genéticas importantes dentro del grupo, y probablemente pueda tratarse de especies nuevas dentro del grupo labiosus, aunque fltan
#estudios más etallados para confirmalor. El linaje del norte de COlombia paraece también corresponder a una unidad evolutiva independiente, por lo que lo más
#probable es que se trate de una nueva especie.
