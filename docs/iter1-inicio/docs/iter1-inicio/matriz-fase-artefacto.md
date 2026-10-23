Estados: **Borrador** (primera versión), **Base** (acordado), **Refinado** (mejorado), **Final** (entregado), — (no aplica).

| Artefacto | Inicio | Elaboración | Construcción | Transición |
|---|---|---|---|---|
| Documento de Visión | Base | Refinado | — | Final |
| SRS breve | Borrador | Base | Refinado | Final |
| Casos de uso | Borrador (ista) | Base | Refinado | Final |
| Diagrama de actividad (proceso crítico) | Base | Refinado | — | — |
| Diagrama de clases | — | Base | Refinado | Final |
| Diagrama de secuencia | — | Base | Refinado | — |
| Diagrama de estados (Cita) | — | Borrador | Base | Final |
| Casos de prueba | — | Borrador | Base | Final |
| Manual de usuario | — | — | Borrador | Final |

Justifiación:
**Documento de visión**: Establece una vista panorámica del proyecto, stakeholders, alcance, necesidades a cubrir
y problemas a resolver, se establece como base ya que es escencial para el desarrollo de los demas artefactos.

**SRS breve**: Documento que detalla los requerimientos funcionales y no funcionales, se desarrolla un borrador
para establecer los primeros requerimientos sin llegar a ser detallados.

**Casos de uso**: Describen cómo interactúan los usuarios (actores) con el sistema para lograr un objetivo, se
establece como un borrador lista que solo muestra los casos de uso a usar para luego detallarlos

**Diagrama de actividad**: Modela el flujo paso a paso de un proceso importante del negocio, con decisiones y rutas alternativas. Ayuda a entender y validar la lógica del proceso más delicado. Por eso solo se refina en las primeras fases y no hace falta mantenerlo después.

**Diagrama de clases**: Muestra la estructura estática del sistema: clases, atributos, métodos y relaciones entre ellas, se desarrolla un primera versión para ir entendiendo como se va a relacionar cada pieza del sistema y seguidamente refinar las relaciones.

**Diagrama de secuencia**: Muestra como se desarrolla la conversación entre todas las partes en el tiempo, se desarrolla una primera versión para entender el proceso temporal
del sistema y luego refinar la estructura. 

**Diagrama de estados**: Describe los estados por los que pasa un objeto con ciclo de vida complejo (aquí, una Cita: pendiente, confirmada, cancelada, completada) y los eventos que provocan cada cambio. Evita inconsistencias en las reglas de negocio. Aparece desde Elaboración porque requiere conocer ya el dominio.

**Casos de prueba**: Definen entradas, pasos y resultados esperados para verificar que el sistema cumple los requisitos. Se derivan de los casos de uso y del SRS. Empiezan en Elaboración como borrador y se completan para validar el producto en Transición.

**Manual de usuario**: Explica a los usuarios finales cómo utilizar el sistema. Solo tiene sentido cuando el producto ya está casi definido, por eso nace en Construcción y se entrega como versión final en Transición.
