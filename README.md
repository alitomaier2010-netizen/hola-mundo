# Hola Mundo — El taller del programador

**Actividad 2 — El taller del programador** · Laboratorio de Programación · 5.º 3.ª A-B · E.E.S.T. N.º 1 «Eduardo Ader»

Configuración del entorno de desarrollo (VS Code + MinGW/GCC vía MSYS2) y primer programa de consola en C++.

- Estudiante: **Alexis Maier**
- Compilador verificado: `g++ (Rev2, Built by MSYS2 project) 14.2.0`
- Extensiones de VS Code: C/C++ (Microsoft), C/C++ Extension Pack y Code Runner

## Datos institucionales

- **Institución:** E.E.S.T. N.º 1 «Eduardo Ader» — Vicente López
- **Curso:** 5.º 3.ª A-B
- **Materia:** Laboratorio de Programación (LPR)
- **Profesor:** Prof. York
- **Actividad:** 2 — Hola Mundo

## Presentación de la Actividad

Primer programa en C++ y análisis del entorno de desarrollo: instalación, compilación y ejecución, junto con el cuestionario técnico de la actividad.

## Integrantes y roles

| Integrante | Rol / tarea asignada | Aporte individual |
|---|---|---|
| Alexis Maier | Implementación del programa, configuración del entorno, capturas e informe | [hola-mundo](https://github.com/alitomaier2010-netizen/hola-mundo) |

## Requisitos e instalación

1. **Git** instalado para clonar el repositorio.
2. **Editor de código** (VS Code con extensiones de C/C++, o Visual Studio Community).
3. **Compilador g++** (MinGW-w64 / MSYS2) agregado al `PATH` del sistema.
4. Clonar y situarse en el directorio:

```bash
git clone https://github.com/alitomaier2010-netizen/hola-mundo.git
cd hola-mundo
```

## Estructura

```
holamundo/
├── .gitignore
├── README.md
├── LICENSE
├── capturas/
│   ├── gpp_version.png            versión del compilador
│   ├── extensiones_vscode.png     extensiones instaladas
│   └── ejecucion_hola_mundo.png   compilación y ejecución
├── docs/
│   └── InformeProyectoHOLAMUNDO.pdf
└── src/
    └── main.cpp
```

## Compilar y ejecutar (PowerShell, desde la raíz del repositorio)

```
g++ src/main.cpp -o src/holamundo.exe
.\src\holamundo.exe
```
