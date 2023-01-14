[![SonarCloud](https://sonarcloud.io/images/project_badges/sonarcloud-orange.svg)](https://sonarcloud.io/summary/new_code?id=fastAPIsemillero20223)
[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=fastAPIsemillero20223)](https://sonarcloud.io/summary/new_code?id=fastAPIsemillero20223)

# Comandos
## Instalar dependencias
`pip install --no-cache-dir --upgrade -r requirements.txt`
## Ejecutar el servicio
`uvicorn app.main:app --host 0.0.0.0 --port 8000`
## Ejecutar pruebas unitarias
`python -m unittest discover tests`
## Compilar Docker
`docker build -t devco/fast-api-example:latest .`
