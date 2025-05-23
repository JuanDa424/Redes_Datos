# Redes_Datos


---

## Scripts incluidos

### `analisis_red.py`

Este script simula un conjunto de operaciones relacionadas con redes de datos, incluyendo:

- Escaneo de puertos comunes (22, 80, 443, etc.).
- Simulación de monitoreo de CPU, RAM y latencia de un servicio como Moodle.
- Verificación de posibles alertas por sobrecarga o mal funcionamiento.
  
Su objetivo es mostrar cómo se podrían implementar pruebas básicas de seguridad y rendimiento en una solución cloud orientada a servicios educativos.

### `despliegue_backup.py`

Este script simula dos tareas clave del proceso de despliegue en la nube:

1. **Despliegue progresivo** de servicios (correo, Moodle, pagos, etc.) con tiempos controlados.
2. **Respaldo automático** de datos con generación de archivos simulados por fecha.

Estos ejemplos permiten entender cómo se automatizarían tareas comunes en una arquitectura moderna, mejorando la disponibilidad y reduciendo riesgos de pérdida de información.

---

## Herramientas utilizadas

- **Python 3.x**
- Librerías estándar (`socket`, `datetime`, `random`, etc.)
- Simulación de comportamientos reales para uso académico

---

## Diagrama de Arquitectura

![Arquitectura de Solución Cloud](arquitectura_red.png)

El diagrama muestra los principales componentes en la nube: servicios web, base de datos, almacenamiento, monitoreo y usuarios remotos.

---

## Métricas de Impacto (Simuladas)

- Disponibilidad proyectada: >99.5%
- Tiempo medio de respuesta reducido en un 30%
- Tiempo de recuperación ante fallos: <10 minutos
- Satisfacción del usuario: >80% esperada

---

## Licencia

Este repositorio se encuentra bajo la licencia MIT. Puedes reutilizarlo, modificarlo y compartirlo libremente con fines educativos o de aprendizaje.

---

## Contacto

Este repositorio forma parte de una simulación académica para fines de evaluación y formación en arquitectura cloud y automatización con Python.

