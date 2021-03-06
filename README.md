[![Github Actions Status for
thiagomathiassimon/calculadora1](https://github.com/thiagomathiassimon/calculadora1/workflows/Integracao_Continua_de_Java_com_Maven/badge.svg)](https://github.com/thiagomathiassimon/calculadora1/actions)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=thiagomathiassimon_calculadora1&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=thiagomathiassimon_calculadora1)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=thiagomathiassimon_calculadora1&metric=coverage)](https://sonarcloud.io/component_measures?id=thiagomathiassimon_calculadora1&metric=coverage)

# Calculadora com C.I.
Utiliza 3 ambientes:
- dev - Desenvolvimento
- hmg - Homologação
- prd - Empacotamento

Pipeline
- dev - Compilação
- hmg - Compilação, Testes, Análise de Código e Cobertura de Código
- prd - Empacotamento

<br>
- Utiliza o Apache Maven para a automatização da construção.
<br>
- A pasta test contêm os testes unitários do projeto utilizando JUnit 4.
<br>
- A cobertura do código é realizada através do JaCoCo.
- <br>
