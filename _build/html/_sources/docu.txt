

Sistema de Gestión de Documentos Estructurados
==============================================



1. Introducción
------------------------

El sistema manejará la documentación en formato rts "reStructuredText" en un lenguaje de marcas muy fácil para su implementación y muy versátil para crear documentos. 

El sistema genera en base a una estructura definida en un archivo “archivo.rst” una estructura de documentos, Desde el usuario utilizando software libre como sphix 1.3.1. se genera archivos html, los mismos que son actualizados mediante un script shell en el servidor.

Este sistema esta compuesto de subsistemas los cuales son:

* Subsistema de Creación Documentos Estructurados
* Subsistema de Flujo de Documentos
* Subsistema de Gestor de Documentos

Este sistema permitirá a los usuarios mantener actualizados de forma permanente la documentación en un repositorio definido.

2. Estructura de documentos
------------------------------------

Revisada una serie de proyectos como propuesta genérica se puede definir la estructura de documentos dentro un archivo.rst para la carpeta DOCS, el cual permitira documentar el trabajo durante el desarrollo de los proyectos de Software
 

3. Estructura básica propuesta de la carpeta DOCS 
-------------------------------------------------------


.. code-block:: php

            contenido.rts

            documentacion-tecnica/

            guia-de-inicio.rts

            guia-de-instalacion.rts

            manuales/

            aplicación/

            ----------css/

            ----------font/

            ----------img/

            ----------js/

            ----------jquery/
			
            referencias-tecnicas/

            glosario-de-terminos.rts

            anexos/

**DONDE:**

**contenido.rts**, Este archivo contiene la estructura definida para el desarrollo de un determinado trabajo, que puede ser ampliado o simplificado de acuerdo a las necesidades.

**documentacion-tecnica/**, Esta carpeta contiene los archivos de diseño de los sistemas.

**guia-de-inicio.rts**, Este archivo presenta una guía rápida de inicio del sistema.

**guia-de-instalacion.rts**, Este archivo presenta una guia de instalación del sistema.

**manuales/**, Esta carpeta contiene archivos de manuales de usuario, administracion y otros.

**aplicación/**, En esta carpeta se almacenan los archivos de la aplicación, en esta estructura básica solo se presento lo necesario, si se utiliza otros modelos de desarrollo se pueden agregar las carpetas necesarias de acuerdo al trabajo a desarrollar.
 
**referencias-tecnicas/**, Esta carpeta contiene las referencias tecnicas, normativa y / o procedimientos que se emplean para el desarrollo del sistema.


**glosario-de-terminos.rts**, En este archivo se listan los terminos tecnicos utilizados mas importantes en la documentación.

**anexos/**, Esta carpeta contiene archivos complementarios utilizados y bien definidos que pueden ser de origen externo o propio que se utilizan durante el desarrollo de sistemas.



4. Desarrollo de los subsistemas ( a desarrollar con todo el tema técnico)
------------------------------------------------------------------------------

4.1 Subsistema de Creación Documentos Estructurados
------------------------------------------------------

La creación de los documentos estructurados permite uniformar todos documentos, para diferentes propositos, desde simples memoradums, informes

4.2 Subsistema de Flujo de Documentos
--------------------------------------------

Este sistema realiza el seguimiento del flujo que sigue el documento de acuerdo a una estructura de una institución definida.

4.3 Subsistema de Gestor de Documentos
---------------------------------------------

Este sistema permite la administración de documentación centralizada en un repositorio definido
