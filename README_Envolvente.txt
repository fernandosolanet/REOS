
Se va a desarrollar en c�digo de Python un nuevo m�dulo. Este nuevo m�dulo pretende contener el c�digo que nos permita sacar 
la envolvente de vuelo del avi�n F4 para cada peso. 
Partiendo de las gr�ficas de las p�ginas 434 y 433 del documento "F4Manual-1979-T-O-1F-4E-1-Flight-Manual-USAF-Series-F-4E-Aircraft",
se sacan los puntos de cada una de las curvas que representan la envolvente del avi�n para cada uno de los pesos indicados. 
Se recogen todos los puntos en un documento de texto. El input al c�digo debe ser el peso del avi�n cargado. A partir de ese peso, 
el c�digo entrar� en el c�digo correspondiente para los pesos superior e inferior e interpolar� entre los datos de esos dos pesos,
generando un conjunto de datos para el peso deseado. Con estos nuevos datos, el c�digo generar� la envolvente de vuelo del avi�n
para ese peso utilizando aproximaciones polin�micas de alto grado que se ajusten bien y tengan alta regresi�n. 

Archivo "Envolventes.txt"
Primera columna: Valores de n�meros de Mach
Segunda columna: Envolvente para 42777 lb. Altitudes para el correspondiente valor de Mach.
Tercera columna: Envolvente para 43035 lb. Altitudes para el correspondiente valor de Mach.
Cuarta columna: Envolvente para 45472 lb. Altitudes para el correspondiente valor de Mach.
Quinta columna: Envolvente para 46279 lb. Altitudes para el correspondiente valor de Mach.
Sexta columna: Envolvente para 46537 lb. Altitudes para el correspondiente valor de Mach.
S�ptima columna: Envolvente para 48974 lb. Altitudes para el correspondiente valor de Mach.