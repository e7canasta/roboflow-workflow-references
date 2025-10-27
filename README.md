# Roboflow Workflow References

Referencias e implementaciones para Roboflow Workflows.

## Estructura del Proyecto

```
├── core/                    # Componentes principales del motor de workflows
│   ├── core_steps/         # Pasos básicos del workflow
│   ├── enterprise_blocks/  # Bloques empresariales
│   ├── execution_engine/   # Motor de ejecución
│   └── prototypes/         # Prototipos experimentales
├── docs/                   # Documentación y guías
├── examples/               # Ejemplos de implementación
├── notebooks/              # Jupyter notebooks con demostraciones
├── video_analysis/         # Herramientas para análisis de video
└── workflows.py            # Módulo principal de workflows

```

## Instalación

```bash
git clone https://github.com/e7canasta/roboflow-workflow-references.git
cd roboflow-workflow-references
pip install -r requirements.txt
```

## Uso Básico

```python
# Ejemplo básico de uso de workflows
from workflows import handle_describe_workflows_blocks_request

# Describir bloques disponibles
blocks_description = handle_describe_workflows_blocks_request()
print(blocks_description)
```

## Ejemplos

Revisa la carpeta `examples/` para ver implementaciones completas:

- `objects_passing_line_demo.py`: Detección de objetos cruzando líneas
- `path_deviation_demo.py`: Análisis de desviación de rutas  
- `time_in_zone_demo.py`: Tiempo de permanencia en zonas
- `workflows_demo.py`: Demostración general de workflows

## Notebooks

Los notebooks en `notebooks/` proporcionan guías interactivas:

- `workflows.ipynb`: Introducción a workflows
- `clip_classification.ipynb`: Clasificación con CLIP
- `inference_pipeline_rtsp.ipynb`: Pipeline de inferencia RTSP

## Contribuir

1. Haz fork del repositorio
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit tus cambios (`git commit -am 'Añadir nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Crea un Pull Request

## Licencia

Ver archivo [LICENSE](LICENSE) para detalles.
