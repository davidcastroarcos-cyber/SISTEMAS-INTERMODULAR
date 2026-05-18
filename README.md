# SISTEMAS-INTERMODULAR
# 🇬🇧 Red BridgeWay English: El corazón tecnológico de mi academia

¡Hola! Soy **David Castro** y este es mi proyecto para el módulo de Sistemas Operativos de 1º de SMR. 

Más que un simple trabajo de clase, he querido diseñar cómo sería de verdad la infraestructura informática de una escuela de idiomas: **Red BridgeWay English**. Mi objetivo era sencillo pero ambicioso: que los profes no tengan que pelearse con el ordenador y que los datos de los alumnos estén blindados.

---

##  ¿Cómo pensé este proyecto?
En una academia real, no todos los puestos de trabajo son iguales. Por eso, decidí no usar el mismo sistema para todo:

* **Windows 11 en Recepción:** Para que todo el software de gestión y las impresoras funcionen a la primera, sin líos de drivers.
* **Ubuntu (Linux) en las Aulas:** Como los profes suelen traer pendrives de casa, elegí Linux para evitar que los virus campen a sus anchas. Además, ¡arranca volando!

---

##  ¿Qué hay debajo de todo?

### 1. El Laboratorio (VirtualBox)
Nadie construye una casa sin planos. Antes de tocar un equipo real, monté todo en **VirtualBox**. Me sirvió para ajustar la RAM y el disco de forma que, cuando un profe ponga un vídeo en clase, el ordenador no se quede "colgado".

### 2. Particionado con Cabeza
Esto es algo que aprendí en clase y que he aplicado a rajatabla: **he separado el sistema operativo de los datos**. He creado una partición de **50GB** para el sistema. ¿El motivo? Si Windows decide dar problemas un lunes por la mañana, los exámenes y reportes de los alumnos están a salvo en su propia partición.

### 3. Alumnos y Grupos bajo control
Usando la terminal de Ubuntu, he creado una estructura real de usuarios. Verás en el documento cómo he gestionado:
- El grupo `clase1`.
- Los perfiles de `alumno1`, `alumno2` y el del `profesor1`.
Aquí no hay contraseñas apuntadas en post-its; cada uno tiene su sitio.

### 4. Blindaje y Normas
He limpiado los sistemas de telemetría y rastreos innecesarios para que vayan más ligeros. Además, al entrar en el equipo, los alumnos se encuentran con nuestras **"NORMAS CLASE"
