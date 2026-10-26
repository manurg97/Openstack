# Entorno de pruebas de OpenStack

## 1. Introducción

Un entorno de pruebas de OpenStack permite instalar y probar sus servicios
antes de utilizarlos en un entorno de producción.

## 2. DevStack

DevStack es una herramienta que permite instalar y configurar OpenStack
en un entorno de desarrollo y pruebas.

Se utiliza principalmente para aprender cómo funciona OpenStack y
experimentar con sus diferentes componentes.

## 3. Requisitos básicos

Para preparar un entorno de pruebas se recomienda disponer de:

- Un equipo físico o una máquina virtual.
- Un sistema operativo Linux compatible.
- Memoria RAM y espacio de almacenamiento suficientes.
- Conexión a Internet para descargar los componentes necesarios.

Los requisitos concretos dependen de los servicios que se quieran instalar.

## 4. Pruebas de funcionamiento

Una vez instalado OpenStack, se pueden realizar diferentes pruebas:

- **Instancias:** crear y administrar máquinas virtuales con Nova.
- **Redes:** configurar redes virtuales con Neutron.
- **Imágenes:** gestionar imágenes de máquinas virtuales con Glance.
- **Almacenamiento:** crear volúmenes con Cinder.
- **Usuarios:** comprobar la autenticación y los permisos con Keystone.
- **Interfaz web:** administrar los recursos desde Horizon.

## 5. Conclusión

Los entornos de pruebas permiten conocer los componentes de OpenStack,
comprobar su funcionamiento y aprender a gestionar una infraestructura
de nube sin necesidad de utilizar un entorno de producción.
