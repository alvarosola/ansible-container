# Ansible-Container
Proyecto Integrado sobre Ansible Container. 

La configuración despliega una aplicación Flask sobre un servidor web Nginx, en un contenedor Ubuntu.

## Prerrequisitos
* Python 2.7 o Python 3.5
* pip
* setuptools 20.0.0+
* Docker Engine 2.7.0
* Ansible 2.3+

## Pasos a seguir para levantar el escenario:
1. Clonar el repositorio:
```
git clone https://github.com/alvarosola/ansible-container.git
```
2. Acceder a la raíz del proyecto:
```
cd ansible-container/
```
3. Ejecutar "ansible-container build" para construir el proyecto:
```
ansible-container build
```
4. Ejecutar "ansible-container run" para iniciar el proyecto:
```
ansible-container run
```
