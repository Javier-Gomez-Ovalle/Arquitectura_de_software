# Nexo Emprendedor: Informe Técnico de Arquitectura (Modelo C4)

Entrega de la **Actividad 2** de la asignatura **60-95404 Arquitectura de Software**, de la Corporación Universitaria Minuto de Dios.

**Integrantes:** Javier Eduardo Gómez Ovalle, Joel Sebastián Bueno Medina y Juan Pablo Angel Quitian  
**Docente:** Mg. Juan Camilo Rodríguez Villada

## Documento a revisar

👉 [Informe_Tecnico_Arquitectura_C4.md](https://github.com/Javier-Gomez-Ovalle/Arquitectura_de_software/blob/main/Informe_Tecnico_Arquitectura_C4.md)

## Contenido del informe

| # | Sección | Contenido |
|---|---|---|
| 1 | Anexo individual | Borradores elaborados durante la clase |
| 2 | Diagrama de Contexto (Nivel 1) | Actores, sistema y sistemas externos |
| 3 | Diagrama de Contenedores (Nivel 2) | Contenedores, responsabilidades, tecnologías y protocolos |
| 4 | Diagrama de Componentes (Nivel 3) | Descomposición del contenedor `nexo-web` |
| 5 | Matriz de Interfaces y Contratos | Interfaces entre componentes, contratos de API, errores y especificación OpenAPI 3.0 |

## Estructura del repositorio

```text
.
├── README.md
├── Informe_Tecnico_Arquitectura_C4.md
├── borrador_1_contenedores.jpg
├── borrador_2_contexto_simple.jpg
└── borrador_3_flujo_detallado.jpg
```

## Cómo visualizar los diagramas

Los diagramas están escritos en [Mermaid](https://mermaid.js.org/).

- **En GitHub:** se renderizan automáticamente al abrir el archivo `.md`.
- **En VS Code:** abre la vista previa de Markdown con `Ctrl + Shift + V`.
- **En otro visor:** copia el bloque de código del diagrama en [Mermaid Live Editor](https://mermaid.live/) para visualizarlo o exportarlo como imagen.

## Cómo ver la especificación OpenAPI

La sección 5.4 del informe contiene el contrato completo en YAML.

Para visualizarlo de forma interactiva:

1. Copia el bloque YAML desde `openapi: 3.0.3` hasta el final del bloque.
2. Pégalo en [Swagger Editor](https://editor.swagger.io/).

## Instrucciones de revisión

Clone el repositorio ejecutando:

```bash
git clone [https://github.com/Javier-Gomez-Ovalle/Arquitectura_de_software.git](https://github.com/Javier-Gomez-Ovalle/Arquitectura_de_software.git)
cd Arquitectura_de_software
```

El proyecto no requiere instalación de dependencias ni configuración adicional. La entrega corresponde a documentación técnica en formato Markdown.

El informe principal se encuentra en:

```text
Informe_Tecnico_Arquitectura_C4.md
```
