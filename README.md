# Taller-2 Simulación y Despliegue de Robots con Docker y PyBullet  ![Tare-5](1.jpg)  

## Descripción del Proyecto

Este proyecto implementa una infraestructura completa de simulación robótica utilizando contenedores Docker y el motor de física PyBullet. El sistema permite ejecutar simulaciones de tres plataformas robóticas diferentes en entornos aislados y reproducibles, facilitando el desarrollo, testing y despliegue de algoritmos de control y navegación.

## Robots Implementados

### Simulación de Drones Aéreos
**Configuración Técnica:**
- Imagen Docker personalizada con todas las dependencias integradas
- Configuración optimizada de volúmenes para persistencia de datos
- Mapeo de puertos para visualización y comunicación externa
- Integración con controladores de vuelo y sensores virtuales
- Entorno preconfigurado para algoritmos de navegación autónoma

### Robot Baxter de Doble Brazo
**Características de Implementación:**
- Modelado cinemático completo con 7 grados de libertad por brazo
- Simulación de articulaciones y actuadores realistas
- Entorno de trabajo configurado para tareas de manipulación
- Integración de sensores de fuerza y torque virtuales
- Controladores de posición y velocidad implementados

### Robot Humanoide ATLAS
**Aspectos Avanzados:**
- Modelo dinámico completo del humanoide ATLAS
- Configuración de parámetros de control para bipedestación
- Algoritmos de balance y locomoción integrados
- Simulación de sensores IMU y de contacto
- Optimización de rendimiento para simulaciones complejas
