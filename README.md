# Kubernetes Infrastructure

Repositorio para administrar manifiestos Kubernetes
y controlar los despliegues en Oracle Kubernetes Engine (OKE).

## Estructura

- kubernetes/dev: Desarrollo
- kubernetes/hml: Homologación
- kubernetes/prod: Producción
- .github/workflows: Automatización CI/CD

## Estrategia

- Control de versiones con Git.
- Revisión de cambios antes de desplegar.
- Validación de manifiestos.
- Despliegues manuales mediante GitHub Actions.