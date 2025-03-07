```mermaid
graph TD;
    A[Inicio] --> B[Investigación de Tecnologia para Frecuencias Cerebrales];
    A --> C[Investigación de Componentes Relacionados];
    B --> D[Selección de Componentes];
    C --> D;
    D --> E[Diseño de PCB en software EAGLE];
    E --> F[¿Problemas?];
    F -- Si --> G[Consulta con el tutor y rediseño de la PCB];
    F -- No --> H[Fabricación de la PCB e implementación de los componentes en la misma];
    G --> H;
    H --> I[Pruebas con la PCB, detección de datos y procesamiento de frecuencias cerebrales]
    I --> J[Analisis de datos mediante software de procesamiento de señales];
    J --> K[¿Problemas?];
    K -- Si --> L[Consulta con el tutor, investigación de posibles soluciones y resolución de los inconvenientes];
    K -- No --> M[Optimización del diseño y nuevamente pruebas];
    L --> M;
    M --> N[Finalización de detalles esteticos];
    N --> O[Presentación del proyecto ante cada una de las asignaturas junto con su informe];
    O --> P[Fin];


