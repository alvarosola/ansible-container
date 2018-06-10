# Ansible-Container
Proyecto Integrado de fin de grado del ciclo superior Administración de Sistemas Informáticos en Red.

Ansible Container es una tecnología creada para proporcionar un flujo de trabajo centrado en Ansible para construir, ejecutar, probar y desplegar contenedores. 

El objetivo de este proyecto es crear y administrar contenedores a través de una receta Ansible sin tener que utilizar ficheros Dockerfile y desplegar una aplicación Flask que interactue con un servidor web Nginx en un contenedor Ubuntu.

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
