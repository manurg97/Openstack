# Componentes principales de OpenStack

OpenStack es una plataforma de software libre que permite crear y gestionar
infraestructuras de computación en la nube.

## 1. Nova (Compute)

Nova se encarga de gestionar las máquinas virtuales. Permite crear,
iniciar, detener y administrar instancias de computación.

## 2. Neutron (Networking)

Neutron gestiona las redes virtuales de OpenStack. Permite configurar
redes, subredes, direcciones IP y conexiones entre instancias.

## 3. Glance (Image Service)

Glance permite almacenar, consultar y gestionar imágenes de máquinas
virtuales que se utilizan para crear nuevas instancias.

## 4. Cinder (Block Storage)

Cinder proporciona almacenamiento en bloques. Permite crear y gestionar
volúmenes que se pueden conectar a las máquinas virtuales.

## 5. Swift (Object Storage)

Swift proporciona almacenamiento de objetos distribuidos. Se utiliza
para guardar y recuperar archivos y otros datos.

## 6. Keystone (Identity)

Keystone gestiona la identidad y la autenticación de los usuarios.
También controla los servicios y permisos de acceso de OpenStack.

## 7. Horizon (Dashboard)

Horizon ofrece una interfaz web desde la que los usuarios pueden
administrar los recursos de OpenStack.

## 8. Heat (Orchestration)

Heat permite automatizar la creación y gestión de recursos de
infraestructura mediante plantillas.

## 9. Telemetry (Ceilometer)

Ceilometer recopila información sobre el uso de los recursos de la nube,
lo que permite realizar tareas de seguimiento y medición.

## Conclusión

Los componentes de OpenStack trabajan conjuntamente para proporcionar
una infraestructura en la nube. Cada servicio tiene una función
específica, como gestionar máquinas virtuales, redes, almacenamiento,
identidades o recursos.
