# Proyecto-Servidores-De-Colaboracion

INTEGRANTES DEL GRUPO
  Yostin Arias Zuñiga
  Sebastian Leon Cascante
  


Paso a paso del proyecto

Lista de pasos para la instalación de sharepoint server 2019

1. Preparativos Iniciales

    Descarga e instala VirtualBox:
        Visita VirtualBox.org y descarga la última versión.
        Sigue las instrucciones del asistente para completar la instalación.

    Descarga una imagen ISO del sistema operativo:
        Para SharePoint Server, necesitarás un sistema operativo compatible, como Windows Server 2019 o 2022.
        Asegúrate de tener la ISO del sistema operativo que vas a instalar.

    Descarga SharePoint Server:
        Obtén el instalador de SharePoint Server desde el sitio oficial de Microsoft o tu fuente de licencia.

2. Configurar la Máquina Virtual en VirtualBox

    Crear una nueva máquina virtual:
        Abre VirtualBox y haz clic en Nuevo.
        Asigna un nombre a la máquina virtual, selecciona el tipo y versión del sistema operativo (por ejemplo, Windows 2019 o 2022).

    Configurar el tamaño de la memoria:
        Elige una cantidad adecuada de RAM (por ejemplo, 8 GB).

    Configurar el disco duro:
        Crea un nuevo disco duro virtual y asigna suficiente espacio (al menos 40 GB recomendado).
        Selecciona el formato del disco (VDI) y el tipo de almacenamiento (dinámico).

    Configurar las opciones de red:
        Configura la red para que tenga acceso a Internet. Puedes usar NAT o adaptador en puente.

    Cargar la ISO del sistema operativo:
        Selecciona la máquina virtual y haz clic en Configuración.
        Ve a Almacenamiento y carga la ISO del sistema operativo en la unidad óptica virtual.

3. Instalar el Sistema Operativo en la Máquina Virtual

    Iniciar la máquina virtual:
        Selecciona la máquina virtual y haz clic en Iniciar.

    Instalar el sistema operativo:
        Sigue el asistente de instalación del sistema operativo.
        Configura el idioma, zona horaria y las opciones de red según sea necesario.
        Completa la instalación y realiza todas las actualizaciones recomendadas.

4. Instalar Requisitos Previos para SharePoint

    Instalar .NET Framework y otros componentes:
        Abre el Panel de control y accede a Activar o desactivar características de Windows.
        Asegúrate de habilitar .NET Framework, IIS, y otros componentes necesarios.

    Instalar SQL Server:
        Descarga e instala SQL Server (recomendado: versión 2019 o 2022) siguiendo el asistente de instalación.
        Asegúrate de configurar la autenticación en modo mixto y crear una instancia para SharePoint.

5. Instalar SharePoint Server

    Preparar el entorno:
        Asegúrate de que el sistema operativo y SQL Server estén actualizados.
        Configura una cuenta de administrador para SharePoint y SQL Server.

    Ejecutar el instalador de SharePoint:
        Monta o inserta el medio de instalación de SharePoint Server.
        Ejecuta el archivo de instalación y sigue las instrucciones del asistente.
        Elige la opción de instalación completa y proporciona los detalles necesarios.

    Configuración inicial de SharePoint:
        Después de la instalación, abre el Configurador de SharePoint.
        Sigue el asistente para configurar SharePoint, que incluye la configuración de la base de datos y la creación de una granja de servidores.

6. Verificar la Instalación

    Acceder a SharePoint:
        Abre un navegador web y accede a la URL de SharePoint (por ejemplo, http://localhost).

    Verificar que los servicios estén funcionando:
        Asegúrate de que todos los servicios de SharePoint estén activos y funcionando correctamente.

7. Realizar Configuraciones Adicionales

    Configurar sitios y bibliotecas:
        Usa la interfaz de SharePoint para crear y configurar sitios, bibliotecas y permisos.

    Realizar ajustes finales:
        Configura las opciones adicionales según las necesidades específicas de tu entorno.
