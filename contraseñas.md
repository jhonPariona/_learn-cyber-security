 # Contraseñas
 
 ### Hashes
 
 Son algoritmos que cifran las contraseñas
 
 ## LM y NTLM
 
 LM Se debe de desactivar en windows ya que NTLM es más seguro.
 
 ### Mecanismos
 
 **Ingeniería social** Manipula a la persona para obtener la contraseña
 
 **Prueba y error** Probar a mano las contraseñas
 
 **ataque de diccionario** Lista de posibles contraseñas y las probamos con ellas
 
 **Ataque de fuerza bruta** Se prueba todas las posibles contraseñas con sus combinaciones posibles.
 
 ⚙️ Tools
 
 - Ophcrack
 - LOphtCrack
 - Thc Hydra
 - RainbowCrack
 - Medusa

**Rainbow Table** Hashes precomputados(A la hors de crackear es más rápido pero requiere mayor almacenamiento)

**MOnitoreo de red** Escucha los paquetes de la red y roba las contraseñas

## Cifrado de contraseñas

**Salt** Son caracteres aleatorios comun para todos las contraseñas

**peper** caracteres aleatoros únicos para cada contraseña

**AES**

**pbkdf2** Gener un hash del hash previo, asi sucesivamente previe ataques Rain table

**Bycrypt** Más robusta que PBKDF2

**Scrypt** Mucho mas robusta que Bcrypt

**Argon 2** Ganó recientemente competencias a algoritmos robustos pero aún no esta avalado(2020
