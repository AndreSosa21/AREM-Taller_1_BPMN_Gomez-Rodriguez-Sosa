# 📄 Informe Técnico del Taller

## 🔖 Nombre del Taller
Modelado de Proceso del Cliente con BPMN

## 👥 Integrantes del equipo
- Juan Andres Gomez 
- Samuel Andres Rodriguez
- Andrea Julieth Sosa Rodriguez

## 🧠 Descripción general del trabajo
El objetivo del taller fue **modelar en BPMN** el proceso de evaluación posterior a las capacitaciones virtuales dirigidas a **empresas cliente**, garantizando que **todos los empleados** de cada organización **participen y alcancen el 100% de respuestas correctas**. Además, el modelo contempla un **mecanismo de seguimiento diario**, con **reportes por cliente (empresa)** que permiten monitorear el avance y detectar pendientes de forma oportuna.

## 🔧 Proceso de desarrollo
Empezamos entendiendo el proceso actual (Forms → Excel → filtrar por empresa → comparar con listas) y decidimos modelarlo en BPMN para separar claramente responsabilidades y automatización. Primero definimos actores y carriles (Asesora, Plataforma, RRHH del cliente y Empleado) y los datos clave (lista de empleados, respuestas, estado e informe). Luego modelamos el flujo objetivo priorizando lo que reduce trabajo: enlaces únicos por empleado, calificación automática con regla de 100% y reintentos, y un evento diario para generar y enviar el informe por empresa. Finalmente, fuimos ajustando el diagrama agregando compuertas y excepciones comunes (pendientes, reprobados, cambios en listas) hasta dejar un proceso consistente y automatizable.

## 🧩 Análisis del modelo propuesto
Incluya un análisis sobre:
- Cómo se estructura el modelo entregado
- Cómo representa las necesidades del cliente
- Qué supuestos se tomaron

## 📈 Diagrama final entregado
> (Inserte aquí una imagen o enlace al modelo-final.drawio / .asta / PDF)

## 📋 Tabla de actores, entidades o componentes (si aplica)

| Nombre del elemento | Tipo | Descripción | Responsable |
|---------------------|------|-------------|-------------|
| Ej: Paciente        | Actor | Usuario que agenda una cita médica | Cliente |

## 🔍 Investigación complementaria
### Tema investigado:

(Ej: Buenas prácticas BPMN, comparación TOGAF vs C4, principios de seguridad STRIDE, etc.)

### Resumen:
Describa en 2–3 párrafos lo investigado, citando fuentes cuando sea necesario. Incluya cómo se relaciona con el taller.

## 📚 Referencias
- [1] Apellido, Nombre. *Título*. Año. URL o DOI.
- [2] Fuente oficial BPMN: https://www.omg.org/spec/BPMN/

---

_Este documento hace parte de la entrega del taller X del curso AREM (Arquitectura Empresarial) - Universidad de La Sabana._
