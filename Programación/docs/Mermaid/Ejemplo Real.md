<div>
    <style>
        .mermaid-code {
            display: none; /* Oculta el código mermaid por defecto */
        }

        .md-header__button.md-logo img{
            fill: currentcolor;
            display: block;
            height: 3rem;
            width: auto;
        }
        
        body {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        /* Muestra el código mermaid en pantallas grandes */
        @media (min-width: 760px) {
            .mermaid-code {
                display: block;
            }
            .ascii-art {
                display: none; /* Oculta el arte ASCII en pantallas grandes */
            }
        }
        
        /* Muestra el arte ASCII en pantallas pequeñas */
        @media (max-width: 759px) {
            .mermaid-code {
                display: none; /* Asegura que el código mermaid esté oculto en pantallas pequeñas */
            }
            .ascii-art {
                display: block;
            }
        }

        body {
            margin:0px;
        }

        h1 {
            text-align: center;
            font-size: 24px;
        }

        ul {
            list-style-type: none; /* Eliminar puntos de la lista */
            padding-left: 20px; /* Espaciado a la izquierda */
        }

        li {
            margin: 5px 0; /* Espaciado entre elementos de la lista */
        }

        .nivel-1 {
            font-weight: bold; /* Negrita para niveles superiores */
        }

        .nivel-2 {
            margin-left: 10px; /* Sangría adicional para subniveles */
        }

        .nivel-3 {
            margin-left: 20px; /* Sangría adicional para sub-subniveles */
        }
    </style>
</head>
<body>

    <div class="mermaid-code">
        <pre>

<h1>Ejemplo Real </h1>

```mermaid

graph TD

    %% Definir colores y estilos
    classDef filo fill:#FFDDC1,stroke:#FF9F80,stroke-width:2px, font-size:40px;
    classDef antiguedad fill:#C1E1FF,stroke:#5B9BD5,stroke-width:2px, font-size:40px;
    classDef media fill:#D4E157,stroke:#A2BC32,stroke-width:2px, font-size:40px;
    classDef moderna fill:#FFB74D,stroke:#FB8C00,stroke-width:2px, font-size:40px;
    classDef contemporanea fill:#FFFF00,stroke:#e5be01,stroke-width:2px, font-size:40px;
    classDef titulo fill:#FFCCE5,stroke:#FF66B2,stroke-width:2px, font-size:50px;

    A[Historia de la Filosofía] --> B[Edad Antigua]
    A --> C[Edad Media]
    A --> D[Edad Moderna]
    A --> E[Edad Contemporánea]

    %% Edad Antigua y filósofos
    B --> F[Polis]
    F --> G[Sofistas]
    F --> H{Sócrates}
    F --> I{Platón}
    H --> I{Platón}
    I --> J{Aristóteles}

    %% Edad Media
    C --> K[Fe / Razón]
    K --> L[Patrística]
    K --> M[Escolástica]
    K --> N[Crisis de las Escolásticas]
    L --> O{Agustín de Hipona}
    M --> P{Tomás de Aquino}

    %% Edad Moderna
    D --> Q[¿Cómo se conoce?]
    Q --> R[Empiristas]
    Q --> S[Racionalistas]
    R --> T((Sentidos))
    S --> U((Razón))
    U --> V{Kant}
    T --> V
    U --> W{Descartes}

    %% Edad Contemporánea
    E --> X[La Filosofía de la Sospecha]
    X --> Y{Karl Marx}
    X --> Z{Sigmund Freud}
    X --> AA{Friedrich Nietzsche}

    %% Aplicar colores a las ramas
    class B,F,G,H,I,J antiguedad;
    class C,K,L,M,N,O,P media;
    class D,Q,R,S,T,U,V,W moderna;
    class E,X,Y,Z,AA contemporanea;
    class A titulo;

    %% Aplicar color común a los filósofos
    class H,I,J,O,P,V,W,Y,Z,AA filo;
```

Siendo su código el siguiente:

```mermaid title="Mermaid" linenums="1"

graph TD

    %% Definir colores y estilos
    classDef filo fill:#FFDDC1,stroke:#FF9F80,stroke-width:2px, font-size:40px;
    classDef antiguedad fill:#C1E1FF,stroke:#5B9BD5,stroke-width:2px, font-size:40px;
    classDef media fill:#D4E157,stroke:#A2BC32,stroke-width:2px, font-size:40px;
    classDef moderna fill:#FFB74D,stroke:#FB8C00,stroke-width:2px, font-size:40px;
    classDef contemporanea fill:#FFFF00,stroke:#e5be01,stroke-width:2px, font-size:40px;
    classDef titulo fill:#FFCCE5,stroke:#FF66B2,stroke-width:2px, font-size:50px;

    A[Historia de la Filosofía] --> B[Edad Antigua]
    A --> C[Edad Media]
    A --> D[Edad Moderna]
    A --> E[Edad Contemporánea]

    %% Edad Antigua y filósofos
    B --> F[Polis]
    F --> G[Sofistas]
    F --> H{Sócrates}
    F --> I{Platón}
    H --> I{Platón}
    I --> J{Aristóteles}

    %% Edad Media
    C --> K[Fe / Razón]
    K --> L[Patrística]
    K --> M[Escolástica]
    K --> N[Crisis de las Escolásticas]
    L --> O{Agustín de Hipona}
    M --> P{Tomás de Aquino}

    %% Edad Moderna
    D --> Q[¿Cómo se conoce?]
    Q --> R[Empiristas]
    Q --> S[Racionalistas]
    R --> T((Sentidos))
    S --> U((Razón))
    U --> V{Kant}
    T --> V
    U --> W{Descartes}

    %% Edad Contemporánea
    E --> X[La Filosofía de la Sospecha]
    X --> Y{Karl Marx}
    X --> Z{Sigmund Freud}
    X --> AA{Friedrich Nietzsche}

    %% Aplicar colores a las ramas
    class B,F,G,H,I,J antiguedad;
    class C,K,L,M,N,O,P media;
    class D,Q,R,S,T,U,V,W moderna;
    class E,X,Y,Z,AA contemporanea;
    class A titulo;

    %% Aplicar color común a los filósofos
    class H,I,J,O,P,V,W,Y,Z,AA filo;
```
        </pre>
    </div>

    <div class="ascii-art">
    <h1>Historia de la Filosofía</h1>
    <p>Tu pantalla es demasiado pequeña para soportar Gráficos Mermaid</p>
    <ul>
        <li class="nivel-1">Edad Antigua
            <ul class="nivel-2">
                <li>Polis
                    <ul class="nivel-3">
                        <li>Sofistas vs Sócrates</li>
                        
                        <li>Sócrates
                            <ul>    
                                <li>Platón</li>
                                <li>Aristóteles</li>
                            </ul>
                        </li>
                    </ul>
                </li>
            </ul>
        </li>
        <li class="nivel-1">Edad Media
            <ul class="nivel-2">
                <li>Fe / Razón
                    <ul class="nivel-3">
                        <li>Patrística
                            <ul>
                                <li>Agustín de Hipona</li>
                            </ul>
                        </li>
                        <li>Escolástica
                            <ul>
                                <li>Tomás de Aquino</li>
                            </ul>
                        </li>
                        <li>Crisis de las Escolásticas</li>
                    </ul>
                </li>
            </ul>
        </li>
        <li class="nivel-1">Edad Moderna
            <ul class="nivel-2">
                <li>¿Cómo se conoce?
                    <ul class="nivel-3">
                        <li>Empiristas
                            <ul>
                                <li>(Sentidos)</li>
                            </ul>
                        </li>
                        <li>Racionalistas
                            <ul>
                                <li>(Razón)</li>
                                <li>Descartes</li>
                            </ul>
                        </li>
                        <li>Razón + Sentidos
                            <ul>
                            <li>Kant</li>
                            </ul>
                        </li>    
                    </ul>
                </li>
            </ul>
        </li>
        <li class="nivel-1">Edad Contemporánea
            <ul class="nivel-2">
                <li>La Filosofía de la Sospecha
                    <ul class="nivel-3">
                        <li>Karl Marx</li>
                        <li>Sigmund Freud</li>
                        <li>Friedrich Nietzsche</li>
                    </ul>
                </li>
            </ul>
        </li>
    </ul>
</div>

</div>
