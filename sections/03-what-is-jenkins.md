# O que é o [Jenkins][0]?

- Ferramenta de _[continuous integration][1] and [continuous delivery][2]_
- _Fork_ do [Hudson][3] (Oracle)
- _Continuous integration_?
  - Temos isso?
  - Pressupostos
- _Continuous delivery_?
  - Temos isso?
  - Pressupostos

[0]:https://jenkins.io/
[1]:https://martinfowler.com/articles/continuousIntegration.html
[2]:https://dzone.com/articles/8-principles-continuous
[3]:http://hudson-ci.org/


# _Continuous integration_
- Requisitos
  - Repositório: SVN
  - Automação de _build_: Maven
  - Testes: JUnit/Spock
  - Integrar ao _branch_ de _sprint_ frequentemente
  - _Build_ do _branch_ de _sprint_ ao detectar mudanças