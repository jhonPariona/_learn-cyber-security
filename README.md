#  🏆 learn-cyber-security

## 💎Aislamiento

🦜 **Lógico** virtualización de los componentes aislados

🦜 **Fisico** hardware separado (protección de activos de info)

## 💎CCTV

Son cámaras

## 💎Incidente

Acción no planificada

ejem:

🦜 Error de hardware

## 💎Leyes en Perú

🦜 **Ley N° 30999 Ley de ciberdefensa**

🦜 **Ley 30096 Ley de delitos informáticos**

🦜 **Ley de firmas y certificados digitales**
    
 - 🚀 **Hash** caracteres hexadecimales de longitud fija(depende de la función de hash usada). Se usa para verificar la integridad
   
 - 🚀 **Llave asimétrica** se usa para los certificados digitales
   
   
 - 🚀 **Llave simétrica** Se usa para cifrar grandes volúmenes de datos.
   
 🦜 **Ley de protección de datos personales** Art. 2 numeral 6
 
 ## 💎[Divindat](https://www.mininter.gob.pe/content/ciberpolic%C3%AD-contra-delitos-inform%C3%A1ticos)
 
 ## 💎Convenio de budapest
 
 Facilita la extradicción de cibercriminales de los países que forman esta alianza.
 
 Además brindan ayuda mutua entre ellos. EL Perú también pertenece.
 
 ## 💎Manual Tallin
 
 Manual para ciberguerras
 
 ## Triada CID
 
 La **confidencialidad** garantiza la privacidad de los datos mediante la restricción del acceso con el cifrado de la autenticación.
 
 La **integridad** garantiza que la información sea precisa y confiable
 
 La **disponibilidad** garantiza que la información esté disponible a las personas autorizadas.
 
 ## Tipos de Atacantes
 
 **Script Kiddies** Aficionados  utilizan las herramientas existentes o las instrucciones que se encuentran en Internet para llevar a cabo un ataque.
 
 **Hackers Sombrero Blanco** ingresan a las redes o los sistemas informáticos para descubrir las debilidades para poder mejorar la seguridad con permiso previo
 
**Hackers Sombrero Negro** aprovechan las vulnerabilidades para obtener una ganancia ilegal personal, financiera o política
  
**Hackers Sombrero Gris** están en algún lugar entre los atacantes de sombrero blanco y negro. Algunos hackers de Sombrero Gris publican los hechos sobre la vulnerabilidad en Internet para que otros atacantes puedan sacarles provecho.

 **delincuentes cibernéticos** generalmente son grupos de delincuentes profesionales centrados en el control, el poder y la riqueza.
 
 **Los hacktivistas** hacen declaraciones políticas para concientizar sobre los problemas que son importantes para ellos.
 
  **atacantes patrocinados por el estado** reúnen inteligencia o causan daño en nombre de su gobierno.
  
  ## Amenazas
  
  **Amenazas de seguridad internas** 
  
  **Amenazas de seguridad externas**
  
  ## Ciber Guerra
  
  Un país puede constantemente invadir la infraestructura de otro país, robar los secretos de defensa, y recopilar información sobre la tecnología para reducir las brechas en sus sectores industriales y militare
  
  **el malware de Stuxnet** diseñado para dañar la planta de enriquecimiento nuclear de Irán
   
 
 
 ## Etical Hacking
 
 ### Fases
 
 **Reconocimiento**
 
 - OSINT
 
 **Escaning**
 
 - puertos abiertos
 - servidores
 
 **Obtener acceso**
 
 **Mantener acceso**
 
 **Cubrir pistas**
 
 ## Buffer over Flow
 
 Más común en Linux y programas C, se da cuando se le pasa un parámetro de tamaño mayor al que esta declarado en el buffer
 
 ### TIPOS
 
 **Stack over flow**
 
 Se da cuando el programa no gestiona bien los parámetros de entrada
 
 - **stack** es un espacio en memoria que usa el OS para almacenar funciones, variables, etc.
 - **Extensible instruction Pointer(EIP)**  Direccion de la siguiente instrucción
 - **Extensible Stack Pointer (ESP)** dirección más alta del stack (COMIENZO)
 - **Extensible Base Pointer(EBP)** dirección baja del stack
 
 **sol** usar funciones que manejan mejor la memoria como fgets() y no gets(); strncpy() y no strcpy; la mayoria tiene n en su nombre; también usar ASRL
 
 **Heap over flow**
