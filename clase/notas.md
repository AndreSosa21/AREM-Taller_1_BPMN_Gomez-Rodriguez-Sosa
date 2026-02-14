# 🗒️ Registro de Trabajo en Clase - Taller 1

## 📆 Fecha de la sesión
_7 de febrero de 2026_

## 👥 Integrantes presentes
- Juan Andres Gomez 
- Samuel Andres Rodriguez
- Andrea Julieth Sosa 

## 🧠 Actividades realizadas en clase
### Descripción de la sesión de trabajo (Parte 1 - BPMN)

Durante la sesión trabajamos el modelado BPMN del proceso de agendamiento de citas médicas del caso base Clínica Salud Viva. En equipo discutimos cómo funciona el proceso de principio a fin y cómo representarlo correctamente usando los elementos del temario de BPMN: eventos, actividades, decisiones (gateways), flujos y roles.

#### ¿Qué discutimos con el equipo?
- Entendimos el proceso completo: desde que el paciente desea agendar una cita hasta que recibe la confirmación.
- Identificamos las partes del mapa BPMN y su función:
    - Eventos (inicio y fin del proceso).
    - Actividades/Tareas (acciones que realiza el paciente o el sistema).
    - Gateways (decisiones que abren caminos distintos).
    - Flujos (conexiones que muestran el orden del proceso).
- Revisamos las uniones y caminos posibles del proceso:
    - ¿Qué pasa si hay disponibilidad?
    - ¿Qué pasa si no hay disponibilidad?
    - ¿Cómo se ofrecen alternativas (otro médico u otra fecha)?
    - ¿Qué pasa si el paciente acepta o cancela?

#### ¿Qué decisiones de modelado se tomaron?
- Definimos claramente el evento de inicio (paciente desea agendar) y el evento de fin (cita agendada / confirmación enviada).
- Organizamos el flujo en pasos principales:
- Selección de especialidad → selección de médico → selección de fecha → validación/consulta → confirmación.
- Usamos gateways para representar decisiones reales del proceso (principalmente disponibilidad).
- Modelamos rutas alternas:
    - Ofrecer alternativa cuando no hay cupo.
- Decisión del paciente: acepta alternativa o cancela.
- Incluimos el envío/recepción de confirmación por correo o SMS como parte del cierre del proceso.

#### ¿Qué herramientas se usaron?
- **Lluvia de ideas** para aterrizar el flujo y los posibles caminos.
- **Papel** para bocetar el proceso y ordenar las ideas antes de digitalizar.
- **draw.io** para construir el diagrama BPMN final con los símbolos correctos.

#### ¿Qué parte del trabajo se alcanzó a desarrollar?
- Se definió el flujo completo del proceso con:
    - evento de inicio y fin,
    - actividades principales,
    - decisiones (gateways),
    - rutas alternativas (aceptar alternativa / cancelar),
    - confirmación final por correo/SMS.

## 🧩 Boceto inicial del modelo

> ![Primer diagrama realizado en clase](.//boceto-inicial.png)

## 🧩 Correcciones realizadas al boceto inicial
Se identificó que uno de los actores que definimos en el modelo inicial fue la base de datos, pero decidimos retirarla como actor, ya que en BPMN la base de datos no participa como un rol con acciones propias, sino que funciona como un recurso/almacén de información consultado o actualizado por el sistema.
## 🔁 Tareas definidas para complementar el taller

Anote las responsabilidades acordadas entre los miembros del equipo para completar la entrega final:

| Tarea asignada | Responsable | Fecha estimada |
|----------------|-------------|----------------|
| Modelado final en draw.io | Juan Gomez | 12/08 |
| Redacción del informe     | Andrea Sosa | 13/08 |
| Investigación y referencias | Samuel Rodriguez | 13/08 |
