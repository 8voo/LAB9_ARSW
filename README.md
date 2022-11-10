# Lab9-ARSW
### Integrantes
- Sergio Andres Otero
- Enrique González

### Creacion de la maquina virtual
![image](https://user-images.githubusercontent.com/98104282/200717375-fff3a6e8-4cc0-41df-971a-22a09f46529e.png)
![image](https://user-images.githubusercontent.com/98104282/200717704-5baa5f2a-1e9b-420d-a19d-99f2e3144154.png)
### Descarga de ubuntu
![image](https://user-images.githubusercontent.com/98104282/200926819-58394368-6264-4e59-a830-700cf10812d1.png)
### COnectandose a la maquijna virtual
![image](https://user-images.githubusercontent.com/98104282/200929668-0b2bedb0-ab0d-434e-a395-6b7984450ee7.png)
![image](https://user-images.githubusercontent.com/98104282/200929748-083a10f6-a7ac-4f2f-9238-b7268e07792f.png)
### Instalando npm en fibonachi
![image](https://user-images.githubusercontent.com/98104282/200941200-4e95bf55-f7f7-4422-8c33-b74834efe72e.png)
###Agregando regla a la maquina
![image](https://user-images.githubusercontent.com/98104282/200943798-5b5a97b5-b7a6-404d-bd47-173d62d05cbd.png)
### Probando la app
![image](https://user-images.githubusercontent.com/98104282/200944311-8d15e99f-00b6-4f76-9f2a-2fbd89d4bc73.png)
- Para 10000


![image](https://user-images.githubusercontent.com/98104282/200944847-e8324b22-be97-4936-8124-6aad02e0a2e6.png)
- Para 1010000


![image](https://user-images.githubusercontent.com/98104282/200945009-787d7ed1-199f-4fd4-9396-e09a146c0576.png)
- Para 1020000


![image](https://user-images.githubusercontent.com/98104282/200945301-96088c0e-71bf-474b-b9bc-fa65475a4c5f.png)
- Para 1030000


![image](https://user-images.githubusercontent.com/98104282/200945687-049cb48d-6b57-45e9-9b96-821b7537a113.png)
- Para 1040000


![image](https://user-images.githubusercontent.com/98104282/200946006-3e8cd592-ca19-46b0-83ff-8f5f86ba3c0f.png)
- Para 1050000


![image](https://cdn.discordapp.com/attachments/898369871912534016/1040015587587395694/image.png)
- Para 1060000


![image](https://cdn.discordapp.com/attachments/898369871912534016/1040015259806740550/image.png)
- Para 1070000


![image](https://cdn.discordapp.com/attachments/898369871912534016/1040014793848934500/image.png)
- Para 1080000


![image](https://cdn.discordapp.com/attachments/898369871912534016/1040014614651482143/image.png)
- Para 1090000


![image](https://cdn.discordapp.com/attachments/898369871912534016/1040014416554500207/image.png)
### Rendimiento
![image](https://user-images.githubusercontent.com/98104282/200948099-a862e383-46a5-4fd5-83d9-3fb17d83b777.png)
### Haciendo peticiones concurrentes 

### Se cambia el tamaño de la maquina
![image](https://user-images.githubusercontent.com/98104282/200953165-4c931b0c-9f04-45f0-b510-53ea2a628b21.png)
- Pruebas


![image](https://user-images.githubusercontent.com/98104282/200954724-944a2683-01ff-4c53-ad58-9ec1901a37bf.png)
![image](https://user-images.githubusercontent.com/98104282/200954751-b98ea237-5c5e-4610-9a07-837c888cd301.png)
![image](https://user-images.githubusercontent.com/98104282/200954795-86cafb3a-c288-4827-8fa6-878ec07bbd8f.png)
![image](https://user-images.githubusercontent.com/98104282/200954893-ef69d4b2-2c80-4bca-bc8b-b1954cbe2549.png)
![image](https://user-images.githubusercontent.com/98104282/200954996-c8a23fa4-3907-4a6a-b18d-ac1c78e087dd.png)
![image](https://user-images.githubusercontent.com/98104282/200955152-bcef666a-dfb9-447c-86d0-e94153170341.png)
![image](https://user-images.githubusercontent.com/98104282/200955269-ea175b94-fa51-4167-860c-af19c0a317f4.png)
![image](https://user-images.githubusercontent.com/98104282/200955377-1e865452-3790-4890-8546-30f5ebe321ff.png)
![image](https://user-images.githubusercontent.com/98104282/200955475-eecf9fd1-cf4d-44df-9da8-8354a6870f01.png)
- Uso de la cpu


![image](https://user-images.githubusercontent.com/98104282/200955609-67cf3ab5-1161-4fe4-adc9-2b270cc6b7a0.png)
- Peticiones concurrentes


![image](https://user-images.githubusercontent.com/98104282/200956683-c5629893-0f9b-4eba-b7ea-580da8ec438e.png)

### Preguntas primera parte
Preguntas

1. ¿Cuántos y cuáles recursos crea Azure junto con la VM?
Crea 7 recursos
![image](https://user-images.githubusercontent.com/98104282/200959058-69c90eb1-19d6-47d1-bc9e-bac6098c412f.png)
![image](https://user-images.githubusercontent.com/98104282/200959087-269b6b19-9fda-4325-823a-d69849b66098.png)
2. ¿Brevemente describa para qué sirve cada recurso?
- Clave: es la clave ssh con la cual se peude aceder por medio de ssh a la maquina virtual
- vnet: es la red virtual que se creal para la maquina virtual
- Interfaz de red es la tarjeta de red virtual que tiene la maquina creada anteriormente
- VERTICAL_SCALABILITY es como tal la maquina virtual completa
- VERTICAL_SCALABILITY-ip es la dirección IP publica de la maquina vitual
- VERTICAL_SCALABILITY-nsg Es la configuración de seguridad de la maquina virtual
- VERTICAL-SCALABILITY_OsDisk_1_5c1f9d7f83d3451898ce78f5a6a105aa es el disco duro de la maquina virtual creada
3. ¿Al cerrar la conexión ssh con la VM, por qué se cae la aplicación que ejecutamos con el comando npm FibonacciApp.js? ¿Por qué debemos crear un Inbound port rule antes de acceder al servicio?
- Esto pasa ya que la configuracion de seguridad de la maquina por defecto esta hecha para que no acepte peticione por ese puerto, por eso hay que configurarlo
4. Adjunte tabla de tiempos e interprete por qué la función tarda tando tiempo.
5. Adjunte imágen del consumo de CPU de la VM e interprete por qué la función consume esa cantidad de CPU.
6. Adjunte la imagen del resumen de la ejecución de Postman. Interprete:
7. Tiempos de ejecución de cada petición.
8. Si hubo fallos documentelos y explique.
Estas 5 preguntas estan mas arriba explicados
9. ¿Cuál es la diferencia entre los tamaños B2ms y B1ls (no solo busque especificaciones de infraestructura)?
A parte de el tamaño de la ram y el disco duro, tiene mas demora en el tiempo de respuesta y tiene numeros diferentes de E/S maxima por segundo
10. ¿Aumentar el tamaño de la VM es una buena solución en este escenario?, ¿Qué pasa con la FibonacciApp cuando cambiamos el tamaño de la VM?
No es una solucion muy adecuada ya que el tiempo que baja no es muy relevante, el cambio que se ve es mas en el porcentaje de CPU que consume una petición
11. ¿Qué pasa con la infraestructura cuando cambia el tamaño de la VM? ¿Qué efectos negativos implica?
12. ¿Hubo mejora en el consumo de CPU o en los tiempos de respuesta? Si/No ¿Por qué?
En nuestro caso hubo mejora pero de unos pocos segundos cuando se hace una peticion unica


## Parte 2
- ![image](https://cdn.discordapp.com/attachments/898369871912534016/1040122929691762778/unknown.png)
- ![image](https://cdn.discordapp.com/attachments/898369871912534016/1040122966178013214/unknown.png)
- ![image](https://cdn.discordapp.com/attachments/898369871912534016/1040122994162401330/unknown.png)
- ![image](https://cdn.discordapp.com/attachments/898369871912534016/1040123030858375248/unknown.png)
- ![image](https://cdn.discordapp.com/attachments/898369871912534016/1040123060289818694/unknown.png)
- ![image](https://cdn.discordapp.com/attachments/898369871912534016/1040123083559800854/unknown.png)
- ![image](https://cdn.discordapp.com/attachments/898369871912534016/1040123102211887194/unknown.png)
- ![image](https://cdn.discordapp.com/attachments/898369871912534016/1040123138572288050/unknown.png)
- ![image](https://cdn.discordapp.com/attachments/898369871912534016/1040123161401888808/unknown.png)
- ![image](https://cdn.discordapp.com/attachments/898369871912534016/1040123184948723802/unknown.png)
- ![image](https://cdn.discordapp.com/attachments/898369871912534016/1040123203835674625/unknown.png)
- ![image](https://cdn.discordapp.com/attachments/898369871912534016/1040126118373625856/image.png)
- ![image](https://cdn.discordapp.com/attachments/898369871912534016/1040127778495934464/image.png)
- ![image](https://cdn.discordapp.com/attachments/898369871912534016/1040127961036226570/image.png)

- Cuál es el propósito del Backend Pool?

backend pool es el encargado de defnir el grupo de recursos que haran el trafico de una "load-balancing rule" o regla de equilibrio


- ¿Cuál es el propósito del Health Probe?

health probes o sondeo de estado es aquel que detecta el estado del endpoint del equilibrador, determina que instancias del "backend pool" recibiran nuevas conexiones


- ¿Cuál es el propósito de la Load Balancing Rule? ¿Qué tipos de sesión persistente existen, por qué esto es importante y cómo puede afectar la escalabilidad del sistema?.

"Load Balancing Rule" se define como la distribución del trafico entrante a todas las instancias del grupo de backend


- ¿Qué es una Virtual Network? ¿Qué es una Subnet? ¿Para qué sirven los address space y address range?


permite muchos tipos de recursos de Azure, como las máquinas virtuales, para comunicarse de forma segura entre usuarios, con Internet y con las redes locales


- ¿Qué son las Availability Zone y por qué seleccionamos 3 diferentes zonas?. ¿Qué significa que una IP sea zone-redundant?


Availability Zone son las regiones separadas tolerantes a errores o fallos, conectadas todas y evitando asi el fallo total


- ¿Cuál es el propósito del Network Security Group?


Los grupos de seguradad son utilizados para filtrar y monitorear el trafico de los recursos que se da dentro de una "Azure virtual network"






