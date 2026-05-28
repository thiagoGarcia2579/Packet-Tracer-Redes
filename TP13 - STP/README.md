# TP13 - Spanning Tree Protocol (STP)

## Objetivo
Implementar y analizar el funcionamiento del protocolo **Spanning Tree Protocol (STP)** en una red con switches Cisco, con el fin de evitar bucles de capa 2 y garantizar redundancia en la topología.

---

## Desarrollo del práctico

Durante el trabajo práctico se realizó:

- Configuración de una topología con switches interconectados
- Activación del protocolo STP en los dispositivos
- Elección automática del **Switch Root (Root Bridge)**
- Análisis de puertos en estados:
  - Forwarding
  - Blocking
  - Listening / Learning
- Simulación de enlaces redundantes
- Pruebas de falla en enlaces activos
- Observación de la convergencia del protocolo

---

## Funcionamiento de STP

El protocolo STP evita bucles en la red mediante:

- Elección de un switch raíz
- Bloqueo de enlaces redundantes
- Activación de rutas alternativas solo ante fallos
- Reconfiguración automática de la topología

---

## Resultados obtenidos

- Se evitó la formación de loops en la red
- La topología quedó estable bajo STP
- Se identificó correctamente el Root Bridge
- La red reaccionó correctamente ante fallas de enlaces
- Convergencia automática sin intervención manual

---

## Informe

El informe completo del trabajo práctico se encuentra en el archivo adjunto:

 **Informe_TP13.pdf**

---

## 🧠 Conceptos aplicados

- Spanning Tree Protocol (STP)
- Root Bridge
- Redundancia de red
- Puertos bloqueados / forwarding
- Capa 2 (Enlace de datos)
- Convergencia de red

---

## 🛠️ Herramientas utilizadas

- Cisco Packet Tracer
- Switches Cisco
- Simulación de topologías de red
