# sistema-vacunacion-VE
Proyecto de Programación III 2026. 


Estructura de Carpetas:
sistema-vacunacion-venezuela/
│
├── index.html                 # Página principal / Consulta pública (Estilo SENIAT)
├── login.html                 # Pantalla de inicio de sesión unificada para los 3 perfiles
│
├── css/
│   ├── styles.css             # Estilos personalizados institucionales
│   └── responsive.css         # Ajustes para celulares y tabletas
│
├── js/
│   ├── main.js                # Validaciones generales y lógica de formularios
│   └── validador.js           # Lógica específica para consulta por cédula
│
├── assets/
│   ├── img/                   # Logos institucionales, escudos, vectores
│   └── docs/                  # Formatos o plantillas de ejemplo
│
├── admin/                     # Vistas exclusivas del Perfil Master
│   ├── dashboard.html
│   ├── bitacora.html
│   └── gestion-usuarios.html
│
├── centro_salud/              # Vistas exclusivas del Perfil Centros de Salud
│   ├── registro_vacunas.html
│   └── buscar_personas.html
│
└── subregion/                 # Vistas exclusivas del Subregión de Salud
    ├── procesar_solicitud.html
    └── examenes_salud.html