
graph TD
    A[SECTOR CONGRESO / MILENIUM] --> B(ACTIVIDADES CLAVE);
    A --> C(POBLACIÓN RESIDENTE);
    B --> D{FUENTES DE INGRESO};
    C --> D;
    B --> E(TIPO DE VIVIENDA);
    C --> F(CULTURA Y TRADICIONES);

    B --> B1[SERVICIOS PÚBLICOS / GUBERNAMENTALES];
    B --> B2[COMERCIO MINORISTA];
    B --> B3[SERVICIOS PROFESIONALES Y EMPRESARIALES];

    B1 --> D1[Salarios Sector Público];
    B2 --> D2[Ingresos por Ventas/Comercio];
    B3 --> D3[Honorarios Profesionales];

    D1 & D2 & D3 --> G(Alto % de PEA Ocupada);
    G --> H(Viviendas de Nivel Medio-Alto);
    E --> H;

    style B1 fill:#f9f,stroke:#333,stroke-width:2px;
    style B2 fill:#ccf,stroke:#333,stroke-width:2px;
    style B3 fill:#ff9,stroke:#333,stroke-width:2px;
