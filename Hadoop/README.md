<p align="center">
   <br />
   <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQTt_NmX8fT7DhkwK2G9tv940JJ2v6toYrddw&s" width="45%">
   <br />
</p>


# Introducción a Hadoop

Apache Hadoop es un marco de software de código abierto escrito en Java para el almacenamiento distribuido y el procesamiento distribuido de grandes conjuntos de datos en clústeres de computadoras construidos con hardware de bajo costo. Todos los módulos de Hadoop están diseñados con el supuesto fundamental de que las fallas de hardware (de máquinas individuales o racks de máquinas) son comunes y, por lo tanto, deben ser manejadas automáticamente por el marco de software.

El término "Hadoop" no solo se refiere a los módulos básicos mencionados anteriormente, sino también al "ecosistema" o colección de paquetes de software adicionales que pueden instalarse sobre Hadoop o junto a él, como Apache Pig, Apache Hive, Apache HBase, Apache Spark y otros.

## HDFS (Sistema de Archivos Distribuido de Hadoop)

El **Sistema de Archivos Distribuido de Hadoop (HDFS)** es un sistema de archivos distribuido, escalable y portátil escrito en Java para el marco Hadoop. Un clúster de Hadoop tiene nominalmente un único namenode más un clúster de datanodes, aunque hay opciones de redundancia disponibles para el namenode debido a su criticidad. Cada datanode ofrece bloques de datos a través de la red utilizando un protocolo de bloques específico de HDFS. El sistema de archivos utiliza sockets TCP/IP para la comunicación. Los clientes utilizan llamadas a procedimientos remotos (RPC) para comunicarse entre sí.

## MapReduce

Encima de los sistemas de archivos está el motor de MapReduce, que consiste en un JobTracker, al cual las aplicaciones cliente envían trabajos de MapReduce. El JobTracker distribuye el trabajo a los nodos TaskTracker disponibles en el clúster, esforzándose por mantener el trabajo lo más cerca posible de los datos.


