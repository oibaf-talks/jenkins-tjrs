### O que é o [Jenkins][0]?

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


#### _Continuous integration_
- Requisitos
  - Repositório: SVN
  - Automação de _build_: Maven
  - Testes: JUnit/Spock
  - Integrar ao _branch_ de _sprint_ frequentemente
  - _Build_ do _branch_ de _sprint_ ao detectar mudanças

Note:
Comentar sobre SVN flow proposto pela ArqSis.


#### _Continuous delivery_
- 8 princípios
  - The process for releasing/deploying software MUST be repeatable and reliable
  - Automate everything!
  - If something's difficult or painful, do it more often
  - Keep everything in source control
  - Done means “released”
  - Build quality in!
  - Everybody has responsibility for the release process.
  - Improve continuously

Note:
TESTES! AUTOMAÇÃO! SONAR!


#### _Continuous delivery_
- 4 práticas
  - Build binaries only once
  - Use precisely the same mechanism to deploy to every environment
  - Smoke test your deployment
  - If anything fails, stop the line!

Note:
Nexus!!!
