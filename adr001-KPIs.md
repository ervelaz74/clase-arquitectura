# ADR [number]: [Title]

## Context

[Provide context for the decision, including any constraints or requirements that influenced the decision.]
La empresa ACME Insurance tiene dos líneas de negocio, una de seguros de automóvil y otra de seguros del hogar
Cada área tiene su propio departamento IT independiente que está divido en jefe de proyecto IT y Desarrolladores

## Decision
[State the decision that was made, including any options that were considered and rejected.]

Es necesario medir el impacto en el desarrollo de nuevo software sobre los valores de tiempo, dinero y calidad del desarrollo
- Tiempo: se necesita medir tiempo medio para el desarrollo de una nueva API dentro del departamento
- Calidad: 
  - Se necesita medir si cumple por lo requerido por el área de negocio corresondiente
  - La calidad del software desarrollado mediante pruebas unitarias y procesos de validación
  - La calidad del proceso que estará documentado 
- Dinero:
   - Se necesita conocer el presupuesto para cada desarrollo concreto
   - Se necesita medir el coste del desarrollo incluyendo capital humano
   - Se necesita medir el beneficio que reportará el desarrollo, ya sea económico directamente o en mejora de productividad


## Status

[Indicate the current status of the decision, such as "proposed", "accepted", "rejected", "superseded", or "obsolete".]
proposed

## Consequences

[Describe the consequences, both positive and negative, of the decision, including any risks or dependencies.]
Consecuencias positivas: eliminar incertidumbre al inicio del desarrolo sobre los elementos de tiempo, calidad y dinero mencionados anteriormente
Consecuencias negativas: será necesario un esfuerzo inicial pero que será reportado un beneficio directo en cuanto a la optimización de desarrollos.

## Related documents

[List any related documents, such as requirements or design documents, that influenced the decision.]

Documentos de proceso

### References
- https://github.com/joelparkerhenderson/architecture-decision-record
- https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/examples/metrics-monitors-alerts/index.md
- https://github.com/pmerson/ADR-template
- https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/examples/timestamp-format/index.md
- https://cloud.google.com/architecture/architecture-decision-records
