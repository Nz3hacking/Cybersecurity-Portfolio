# 🌐 Configuración de Red Doméstica con TP-Link Archer AX53

**Proyecto de Administración de Redes y Ciberseguridad**

## 📌 1. Descripción del proyecto

Este proyecto documenta la instalación y configuración de un router **TP-Link Archer AX53 (AX3000)** dentro de una infraestructura de red doméstica con servicio de Internet Totalplay.

La implementación tuvo como objetivo mejorar la cobertura inalámbrica, proporcionar conectividad adicional y facilitar la conexión de dispositivos IoT, específicamente una cámara de vigilancia TP-Link Tapo C510W.

El proyecto demuestra la aplicación práctica de conocimientos relacionados con redes LAN/WAN, configuración de routers, conectividad inalámbrica y resolución de problemas de red.

## 🎯 2. Objetivos

- Implementar un router TP-Link Archer AX53.
- Establecer una conexión Ethernet con el router principal.
- Configurar el equipo en modo router independiente.
- Utilizar direccionamiento IP dinámico (DHCP) para la conexión WAN.
- Mejorar la cobertura inalámbrica en áreas exteriores.
- Facilitar la conectividad de dispositivos IoT.
- Aplicar conocimientos de administración y diagnóstico de redes.

## 🖥️ 3. Infraestructura utilizada

| Componente | Descripción |
|---|---|
| Proveedor de Internet | Totalplay |
| Router principal | FiberHome HG6142H7 |
| Router secundario | TP-Link Archer AX53 |
| Tecnología inalámbrica | Wi-Fi 6 (802.11ax) |
| Clase Wi-Fi | AX3000 |
| Bandas inalámbricas | 2.4 GHz y 5 GHz |
| Tipo de conexión WAN | IP dinámica (DHCP) |
| Interconexión | Cable Ethernet |
| Dispositivo IoT | TP-Link Tapo C510W |

## 🏗️ 4. Topología de red

La infraestructura está compuesta por un router principal del proveedor de Internet y un router secundario TP-Link Archer AX53.

```text
                  INTERNET
                     |
                     |
                  TOTALPLAY
                     |
                     |
          +----------------------+
          | FiberHome HG6142H7   |
          | Router principal     |
          +----------------------+
                     |
                     | Ethernet
                     |
          +----------------------+
          | TP-Link Archer AX53  |
          | Modo Router          |
          | WAN: IP Dinámica     |
          +----------------------+
                     |
                Red Wi-Fi
                     |
              +------+------+
              |             |
           2.4 GHz        5 GHz
              |             |
          Dispositivos   Dispositivos
          IoT            compatibles
```

## ⚙️ 5. Proceso de instalación y configuración

### 5.1 Instalación física

Se realizó la instalación del router TP-Link Archer AX53 y su conexión mediante cable Ethernet a la infraestructura del router principal FiberHome HG6142H7.

Esta conexión permite que el equipo secundario reciba conectividad desde la red principal.

### 5.2 Configuración del modo de operación

Se configuró el Archer AX53 para funcionar como **router independiente**.

Este modo permite al dispositivo administrar su propia red local y utilizar funciones de enrutamiento, DHCP y NAT.

### 5.3 Configuración de Internet

Durante el asistente de configuración se seleccionó el tipo de conexión:

**Dynamic IP (IP dinámica).**

Esta modalidad permite obtener automáticamente la configuración de la interfaz WAN mediante DHCP.

### 5.4 Configuración inalámbrica

El Archer AX53 proporciona conectividad mediante las bandas de 2.4 GHz y 5 GHz.

**Banda de 2.4 GHz**

Se utiliza para ofrecer compatibilidad con dispositivos IoT y mejorar la cobertura inalámbrica en zonas alejadas.

**Banda de 5 GHz**

Proporciona conectividad para dispositivos compatibles que pueden aprovechar un mayor rendimiento inalámbrico en condiciones adecuadas.

## 🔍 6. Diagnóstico y solución de conectividad

### Problema identificado

La cámara de vigilancia TP-Link Tapo C510W presentó problemas de conexión con la red inalámbrica del router principal.

Durante el diagnóstico se observaron dificultades para detectar la red Wi-Fi y mantener la conectividad desde la aplicación de administración.

La ubicación exterior de la cámara y la presencia de obstáculos físicos también representaban desafíos para la cobertura inalámbrica.

### Acciones realizadas

1. Revisión de la conectividad del router principal.
2. Comprobación de la banda inalámbrica de 2.4 GHz.
3. Reinicio y revisión de los equipos de red.
4. Restablecimiento y reconfiguración de la cámara.
5. Instalación de un router TP-Link Archer AX53.
6. Configuración de Internet mediante IP dinámica.
7. Comprobación de la señal inalámbrica desde el área exterior.

### Resultado

Después de implementar el Archer AX53, se consiguió detectar la nueva red inalámbrica desde la zona exterior donde se encontraba la cámara.

La incorporación del router proporcionó una alternativa de conectividad para los dispositivos ubicados en esa área.

## 🛡️ 7. Seguridad de red

La implementación permite aplicar principios de seguridad relacionados con la administración de infraestructura.

Entre las consideraciones de seguridad del entorno destacan:

- Protección del acceso administrativo al router.
- Uso de mecanismos de autenticación inalámbrica.
- Administración independiente del router secundario.
- Control de dispositivos conectados a la red.
- Reducción de la exposición de credenciales de administración.
- Consideración de los riesgos asociados con dispositivos IoT.

La configuración de dos routers también permite estudiar conceptos como NAT, direccionamiento privado y separación lógica de redes.

## 📊 8. Resultados obtenidos

| Actividad | Resultado |
|---|---|
| Instalación del Archer AX53 | Completada |
| Conexión Ethernet al router principal | Completada |
| Configuración en modo router | Completada |
| Configuración WAN mediante DHCP | Completada |
| Configuración inicial inalámbrica | Completada |
| Detección de señal Wi-Fi en exterior | Confirmada |
| Inicio de reconexión del dispositivo IoT | Realizado |

## 📚 9. Conocimientos aplicados

Durante la implementación se utilizaron conocimientos de:

- Administración de redes.
- Infraestructura LAN y WAN.
- Protocolo DHCP.
- Enrutamiento IPv4.
- NAT.
- Redes inalámbricas Wi-Fi.
- Conectividad Ethernet.
- Diagnóstico de dispositivos IoT.
- Resolución de problemas de conectividad.
- Fundamentos de seguridad de redes.

## 👨‍💻 10. Autor

**NZX3**

Ingeniería en Ciberseguridad y Auditoría Informática.

**Tipo de proyecto:** Implementación y administración de infraestructura de red doméstica.

**Fecha:** Noviembre de 2026.

---

*Proyecto realizado en una infraestructura doméstica propia con fines educativos y de desarrollo profesional en redes y ciberseguridad.*
