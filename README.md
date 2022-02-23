# Linters y Pre-commit hooks
Este repo se toma como plantilla con el hook de pre-commit y el workflow de github para las CI.
## Linters
- flake8: linter general.
- pylint: Mas robusto que flake8 pero mas pesado.

## Formatters
- black: Arregla el código de forma mas limpia

# Setup
- Crear repositorio a partir de este que es plantilla.
- Instalar todo lo que hay en requirements.txt
- Correr el comando `pre-commit install`

# Setup repositorio existente
- Copiar para la raíz del repositorio
  - .pylintrc
  - .flake8
  - .pre-commit-config.yaml
  - .pylintrc-mandatory
  - .github
  - requirements.txt
- Instalar todo lo que hay en requirements.txt
- Correr el comando `pre-commit install`
