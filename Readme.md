flowchart TD
    A[Inicio] --> B[Pantalla de Inicio de Sesión]
    B --> C{Verificar Credenciales}
    C -->|RRHH| D[Dashboard de RRHH]
    C -->|Gerente| E[Dashboard de Gerente]
    C -->|Jefe| F[Dashboard de Jefe]

    D --> G[Gestión de Empleados]
    D --> I[Cálculo de Pagos]

    E --> J[Gestión de Asignaciones]
    E --> K[Supervisión de Operaciones]
    E --> H[Gestión de Horarios]

    F --> L[Vista General]
    F --> M[Análisis]

    G --> N[Agregar/Editar/Eliminar Empleados]
    G --> O[Visualización de Horarios]
    G --> P[Asignación de Lugares]

    H --> Q[Creación de Horarios]
    H --> R[Edición de Horarios]
    H --> S[Gestión de Horas Extras]

    I --> T[Visualización de Pagos]
    I --> U[Generación de Reportes]

    B --> V[Actualización de Perfil]
    B --> W[Notificaciones]
    B --> X[Desconexión]
