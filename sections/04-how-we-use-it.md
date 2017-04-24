# Como é utilizado aqui?

- Máquina virtual _master_ e _slaves_
  - no próprio _master_
  - configurados em Docker
  - máquinas Windows 7 (para Deplhi XE)

#### _Pipelines_
- _Pipelines_ compostos de
  - _Build_
  - _Deploy_ em DEV
  - _Deploy_ em HML
  - _Delivery_for_PM_


#### Build

- Regra hoje é fazer em _slaves_ Docker ([imagens][1])
- Maioria hoje faz no _master_
- Sem testes...
- Tecnologias suportadas:
  - Java 7
  - Java 8
  - Angular2 (angular-cli)
  - Delphi XE (Object Pascal)


#### Sonar (QA)

- _Jobs_ em separado para Sonar (análise de código)
- Uma vez ao dia
- Primeiro uso de imagens Docker (experimentação sem riscos)

[1]:https://hub.docker.com/r/tramasoli/base-images/