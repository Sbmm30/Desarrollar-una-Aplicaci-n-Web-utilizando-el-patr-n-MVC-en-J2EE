# Desarrollar-una-Aplicaci-n-Web-utilizando-el-patr-n-MVC-en-J2EE
Al finalizar el módulo formativo el alumno será capaz de crear un CRUD mediante una aplicación Web utilizando para ello el modelo MVC y la tecnología J2EE así como su material bibliográfico teniendo en cuenta las medidas de seguridad en el trabajo y del ambiente.

# CASO DE ESTUDIO
En una cooperativa de ahorro y crédito, se necesita mejorar la gestión de préstamos a los
asociados, para esto se ha decidido sistematizar el proceso de solicitudes de préstamos. Por
tal situación se debe realizar un modelo de datos desarrollando una aplicación web con las
siguientes consideraciones.
Las solicitudes de préstamos son realizadas por los asociados, en las cuales deben aportar el
número de cuotas, el monto a prestar, cuando se realiza la solicitud , el motivo de crédito y se
deben relacionar también los soportes de manera virtual: un soporte puede estar organizado
teniendo en cuenta su código, el contenido, el nombre y a que solicitud del préstamo pertenece,
una vez que sea aprobado el préstamo , se deben generar las cuotas pertenecientes a el
numero suministrado en la solicitud, una cuota puede tener como atributos: un consecutivo,
fecha o periodo, valor capital, valor intereses, saldo, el estado si esta cancelada o por pagar y
a que solicitud de préstamo pertenece. Una solicitud tiene un estado en la cual puede tener
los siguientes valores: solicitada, aprobada, rechazada, quien aprueba o rechaza es un usuario
del fondo de asociados, después de verificar información económica del asociado.
Un asociado debe tener como atributos, un código, nombre, estado, apellidos, eps, dni,
aportes, nivel de estudio, salario, número de hijos, teléfono y dirección.
Se ha suministrado el siguiente modelo de datos y modelo funcional, que determina que
funciones hará el sistema:

![image](https://user-images.githubusercontent.com/93630275/174504643-6241552c-97c1-4535-b7b7-7dcb4fe27054.png)
![image](https://user-images.githubusercontent.com/93630275/174504675-7548720b-4f48-4d77-9be6-ffb59b35e73a.png)

**Resolver:**
1. Crear una aplicación Web para gestionar el CRUD del modelo solicitado de la
cooperativa, teniendo en cuenta el patrón MVC y la tecnología J2EE
2. Crear los reportes gráficos y en formato MS Excel respectivos de la aplicación
**(Mínimo 2)**
