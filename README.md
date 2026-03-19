# LDM-Tarea-XPath-DanielJimenez
- Autor: Daniel Jiménez Ramírez
- Profesor: Willman Acosta
- Actividad: AEE. XPath Notebook
# Explicacion actividad
Se pide hacer algunas consultas a un XML usando xPath que contiene varios recursos
# Directorio actividad
/xml/recursos.xml -> Archivo con los recursos.
/xml/recursos.xsd -> Archivo que valida el XML que contiene los recursos.
consultas_xpath.xbook -> Archivo para las consultas realizadas al XML.
# Resolucion de la actividad
Titulo: Reto 1: Filtrado por contenido y estado.
Consulta: /bibliotecaTecnica/recurso[categoria='CSS' and disponible='true']/titulo /string()

Titulo: Reto 2: Atributos y negaciones.
Consulta: /bibliotecaTecnica/recurso[@formato!='PDF']/@id /string()

Titulo: Reto 3: Manejo de múltiples nodos (Autores). 
Consulta: /bibliotecaTecnica/recurso[anio>2015]/autor[1]/string()

Titulo: Reto 4: Consultas de complejidad técnica (Nivel y Categoría).
Consulta: /bibliotecaTecnica/recurso[(categoria="xPath" or categoria="XSLT") and nivel="5"]/titulo /string()

# Tecnologias usadas y entorno
- XML, XSD, XPath
- Visual Studio Code
