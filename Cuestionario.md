# TECNOLOGICO NACIONAL DE MEXICO
## INSTITUTO TECNOLOGICO DE MILPA ALTA II
### **Cuestionario 2: Migración de una base de datos en MariaDB**
**Gonzalez Garcia Daniela Zoe**
No. Control: **241190095**
Ingenieria en Sistemas Computacionales
Docente: Ing. Diego Alberto Bollas Paredes
26/11/2026

---

## Responde las siguientes preguntas

1. ¿Por qué se hace un respaldo antes de migrar?
**Para proteger la información y evitar perder datos si ocurre algún error durante la migración.**

---

2. ¿Para qué sirve la opción --single-transaction?
**Permite realizar una copia consistente de la base de datos sin bloquear las tablas, siempre que se utilice un motor compatible como InnoDB.**

---

3. ¿Qué diferencia hay entre exportar con y sin --databases?
**Con --databases se incluye la creación de la base de datos en el respaldo, sin esta opción, solamente se exportan sus tablas y datos.**

4. ¿Qué dos pruebas permiten confirmar que los datos migraron sin pérdidas?
**Comparar la cantidad de registros de las tablas y realizar consultas para comprobar que la información coincida entre ambas bases de datos.**

---

5. Si el destino estuviera en otro servidor, ¿qué paso adicional sería necesario?
**Transferir el archivo de respaldo al otro servidor y restaurarlo ahí, verificando que exista conexión y acceso al servidor de destino.**