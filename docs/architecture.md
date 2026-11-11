# Visión conceptual del producto

> Este documento presenta a NeroMusic como producto: qué es, qué problema resuelve, qué capacidades ofrece y qué tecnologías generales involucra. No describe su implementación interna, su organización técnica ni sus mecanismos de funcionamiento. Esa información forma parte del valor privado del producto.

## Qué es

NeroMusic es un producto privado y comercial para salas de IMVU. Ofrece música personalizada y conversación automatizada, y está pensado para que una comunidad pueda sostener esa experiencia sin depender de un operador permanente.

El producto combina entretenimiento, interacción con usuarios y administración del servicio en una misma propuesta.

## Problema que resuelve

- Salas que necesitan música sin depender de una persona dedicada.
- Pedidos de música difíciles de coordinar dentro de la comunidad.
- Atención repetitiva de usuarios y consultas dentro de la sala.
- Operación de varias salas con criterios centralizados.
- Necesidad de administrar y supervisar el servicio a distancia.
- Conversaciones con IA que se sientan naturales dentro de cada comunidad.

## Capacidades del producto

- Reproducción musical bajo demanda.
- Búsqueda y selección de contenido musical.
- Listas de reproducción y control de la reproducción.
- Gestión de múltiples salas.
- Interacción automatizada con usuarios.
- Conversación con inteligencia artificial.
- Personalidades configurables por sala.
- Panel administrativo para gestionar salas y clientes.
- Supervisión general del servicio.
- Operación desatendida.

## Tecnologías generales

- Node.js
- SQLite
- WebSockets
- Inteligencia artificial
- Procesamiento multimedia
- Linux

Las tecnologías se presentan como áreas de experiencia. La forma en que se integran y el diseño interno del producto se mantienen privados.

## Diagrama de áreas funcionales

El diagrama muestra únicamente las grandes áreas funcionales del producto, sin relaciones, dependencias ni componentes técnicos: [`diagrams/architecture.md`](../diagrams/architecture.md).

## Valor del producto

NeroMusic permite que una sala ofrezca música y conversación con una experiencia cuidada, sin convertir la operación en una tarea permanente. La administración centralizada y la posibilidad de operar varias salas amplían el valor para clientes que gestionan más de una comunidad.

El producto está operativo en producción y ha sido validado mediante pruebas funcionales en salas reales.

## Alcance de esta documentación

Esta presentación se limita a la propuesta de valor, las capacidades y las áreas de experiencia. No incluye información sobre cómo se construyó el producto, cómo se integra con la plataforma ni cómo se mantiene en producción. Esa información es privada y forma parte de la propiedad intelectual de NeroMusic.
