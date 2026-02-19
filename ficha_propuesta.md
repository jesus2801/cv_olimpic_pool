# Ficha de Propuesta de Proyecto Final

**Ingeniería de Sistemas — 202610**

Esta plantilla guía la formulación de temas de Proyecto Final con enfoque de Diseño de Solución Tecnológica. Se espera que cada propuesta describa un problema real y conduzca a una experiencia mayor de diseño: definición de alcance y objetivos, levantamiento de requerimientos, evaluación de alternativas, diseño de arquitectura e implementación de un producto funcional, incorporando estándares de ingeniería y restricciones realistas (tiempo, recursos, calidad, seguridad y operación), en línea con el lineamiento ABET.

---

## Información General

| Campo | Detalle |
|---|---|
| **Título del tema** | Sistema de riesgo y control estadístico para piscina semiolímpica |
| **Docente proponente** | Margarita Rosa Gamarra Acosta |
| **Co-asesor(es) (opcional)** | |
| **Área / línea** | Ingeniería de Software – Inteligencia Artificial – Visión por Computadora – Control de Calidad Industrial |
| **Nº de estudiantes sugerido** | 3 estudiantes (por componentes de visión por computadora, plataforma de software + despliegue del sistema) |

---

## Descripción corta

Debido al aumento de personas que están comenzando a usar los espacios de natación que ofrece la universidad del Norte, es pertinente tener un sistema de control de riesgo y control estadístico para así brindar bienestar y una mejor calidad de entrenamiento a quiénes desean acceder a dichos espacios. Actualmente, la detección temprana de situaciones de riesgo, como un posible ahogamiento, depende casi exclusivamente de la supervisión humana, lo que puede resultar insuficiente en escenarios de alta afluencia.

Este sistema consistirá en una cámara instalada en la piscina semiolímpica de la universidad del Norte, la cual recopilará información para ser procesada mediante un modelo YOLO que utilice "Computer Vision" y logre detectar cuándo una persona está en riesgo de ahogamiento y a su vez pueda monitorear sus estadísticas durante el entrenamiento para que al final de este pueda recibir retroalimentación objetiva sobre su actividad física.

---

## Objetivo

Diseñar e implementar un sistema inteligente basado en visión por computador que permita detectar situaciones de riesgo de ahogamiento y realizar el monitoreo estadístico del desempeño de nadadores en la piscina semiolímpica de la Universidad del Norte, con el fin de mejorar la seguridad, el bienestar y la calidad del entrenamiento de los usuarios.

---

## Alcance propuesto

El proyecto está dirigido a estudiantes y usuarios de la piscina semiolímpica de la Universidad del Norte, con especial enfoque en la comunidad universitaria que practica natación como actividad deportiva o de acondicionamiento físico.

El sistema contempla la configuración e instalación de una cámara ubicada estratégicamente para captar la figura de los nadadores dentro de cada carril de la piscina semiolímpica. La información visual recolectada será procesada mediante un modelo de detección basado en YOLO y técnicas de visión por computador, con el propósito de identificar comportamientos asociados a riesgo de ahogamiento y recopilar métricas básicas del entrenamiento.

**Incluye:**
- Captura de video en tiempo real desde una cámara fija instalada en la piscina.
- Procesamiento de imágenes mediante un modelo de visión por computador basado en YOLO.
- Detección de patrones de riesgo asociados a posibles situaciones de ahogamiento.
- Recolección y análisis de estadísticas básicas del entrenamiento (tiempo de actividad, presencia por carril, patrones de movimiento).
- Generación de retroalimentación general sobre la sesión de entrenamiento.

**No incluye (para acotar):**
- Intervención directa en tiempo real por parte del sistema (rescate físico del nadador).
- Sustitución del personal de salvavidas o supervisión humana.
- Análisis médico o diagnóstico de condiciones de salud de los usuarios.

---

## Riesgos

Manejo de casos especiales como invasión del carril, oclusiones entre nadadores y calidad del video que pueden afectar la precisión del modelo de detección.
