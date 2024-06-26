# Presentación
### **Equipo No. 8** 
- González Canul Mariana Estefanía 
- Osorno Tah Astrid Alejandra
- Villanueva Díaz Luisa Cristina

### Descripción Actividad
Realizar un Jupyter Notebook utilizando el kernel iRacket con los 10 ejercicios brindados en plataforma.

# Instalación y Configuración del Notebook
## **Prerequisitos**
- [Racket](https://racket-lang.org/)
- [Python](https://www.python.org/downloads/)
- ZeroMQ
  - en Debian/Ubuntu Linux: instala el paquete `libzmq5` 
  - en RedHat/Fedora (Linux): instala el paquete `zeromq`
  - en MacOS con Homebrew: ejecuta `brew install zmq`
  - en Windows, esta instalado automáticamente por el paquete `zeromq-r-lib` de Racket
  - Para otros sistemas operativos, consulte http://zeromq.org

## **Agregando Racket al PATH**
Entre a Propiedades del sistema, en Variables de entorno agregue la ruta de acceso del directorio donde está instalado Racket al `PATH` del sistema.

![image](https://github.com/marglezc/Programacion-Funcional-EQ08/assets/144637940/2a594f71-81cd-46ca-9001-618a248c9906)
![image](https://github.com/marglezc/Programacion-Funcional-EQ08/assets/144637940/23764360-e132-4916-989c-589005715128)
![image](https://github.com/marglezc/Programacion-Funcional-EQ08/assets/144637940/d44ee4aa-5742-4418-a11e-ffc90ba7a1b0)


Si no sabe donde se encuentra en su equipo, puede buscarlo como Racket Folder.

![image](https://github.com/marglezc/Programacion-Funcional-EQ08/assets/144637940/2d269d07-29ac-4104-a5f2-2683000869ab)

## **Instalación de Jupyter Notebook**
Ejecute `pip install notebook` en la línea de comandos.
Para ejecutar el notebook, escriba `jupyter notebook`.

## **Instalación de iRacket**

Abra la línea de comadnos. Para instalar el paquete de iRacket, escriba `raco pkg install iracket`.
Después, registre el kernel de iRacket con Jupyter ejecutando `raco iracket install`.

# Descripción Problemas
- [Problemas](https://github.com/marglezc/Programacion-Funcional-EQ08/blob/Archivos/Ejecuci%C3%B3nProblemas.md)

# Notebook
Para abrir el notebook, descargue el archivo Proy02_E08.ipynb. Ejecute `jupyter notebook` en la línea de comandos y busque el archivo en Notebook.
Para ejecutar un comando una vez abierto el notebook, presione shift + Enter.
