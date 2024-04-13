# Boas práticas

* Pipeline é a única forma de deploy.
* O pipeline deve ser o mais rápido possível.
* A primeira etapa do pipeline (build) só pode ser gerado uma vez.
* Build independente do ambiente.
* Ambientes iguais/semelhantes ao ambiente de produção. Quanto mais semelhante o ambiente, mais garantias temos que o deploy vai funcionar e os testes vão dar feedback real.
* Ambientes efêmeros. Idealmente, criamos todo o ambiente do zero, para não levar nenhuma "sujeira" de instalações e testes anteriores.
* Ferramentas de deploy iguais para diferentes ambientes.

### Pipeline review

Unit Test --> Aceitação Automatizada --> Homologação --> Produção

* O importante é que os testes rápidos fiquem à esquerda, e que cada ambiente à direita se aproxime do ambiente de produção.

---
