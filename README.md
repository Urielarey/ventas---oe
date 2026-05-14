# Análisis de Ventas - Organización Empresarial

## Integrantes del equipo
| Rol | Nombre | Responsabilidad |
|-----|--------|----------------|
| P1 - Líder y Organizador (Hugo) | Uriel Alvarez Rey | Inicialización del repositorio y estructura |
| P2 - Desarrollador Técnico (Paco) | Uriel Alvarez Rey | Desarrollo del script de análisis |
| P3 - Revisor y QA (Luis) | Uriel Alvarez Rey | Revisión de código y cierre del PR |

## Escenario elegido
Escenario B - Análisis de Ventas de una Pequeña Empresa

## Dataset utilizado
- **Nombre:** sales_sample_2024.csv
- **Fuente:** https://gist.github.com/khanusama20/ee33c2869dd5cf3cebdf020be1ca43f6
- **Descripción:** Registros diarios de ventas del año 2024 con columnas id, sales_date y sales_amount

## Estructura del repositorio
ventas---oe/
├── datos/
│   └── ventas.csv
├── scripts/
│   └── analisis_ventas.py
├── resultados/
│   └── grafico_ventas.png
├── README.md
└── .gitignore  

## Instrucciones para ejecutar el script
1. Clonar el repositorio
2. Instalar dependencias: `pip install pandas matplotlib`
3. Navegar a la carpeta scripts: `cd scripts`
4. Ejecutar: `python analisis_ventas.py`

## Gestión del proyecto
El proyecto fue gestionado mediante Jira con los siguientes issues:
- SCRUM-1: Inicialización del repositorio y estructura de carpetas
- SCRUM-2: Desarrollo del script de análisis de ventas
- SCRUM-5: Revisión de código, documentación y cierre del Pull Request