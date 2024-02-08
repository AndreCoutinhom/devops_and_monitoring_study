# Servidor de integração contínua

![image](https://github.com/AndreCoutinhom/devops_and_monitoring_study/assets/91290799/e96a6052-0c54-40a9-a532-564166c15fb9)

* Existem casos por questão de tempo em que não podemos realizar todos os testes necessários ou o projeto é tão complexo que não pode ser testado integralmente em uma máquina local.

* Em algum momento precisamos encontrar um local que realmente será capaz de testar todo o projeto, e este é o CI Daemon ou server de integração. Esse servidor irá garantir que a cada modificação seja realizado um novo teste, então o repositório é sempre checado e builds contínuos são uma realidade.

* A prática de integração contínua não especifica que o CI Daemon é necessário, mas hoje em dia podemos considerar como uma obrigação nos projetos. Contudo, só porque utilizamos um server dessa natureza estamos praticando integração contínua, uma ação é realizada por pessoas.

* O CI Daemon realiza builds contínuos e notifica os desenvolvedores se alguma alteração se deu corretamente ou não. Normalmente esses softwares já possui um test board que oferecem os dados do build, então as informações e relatórios são de fácil acesso.

* Existem alguns serviços no mercado que podem ser instalados localmente, o Jenkins é um exemplo. Existem também serviços na nuvem já associados. É importante que apenas que o servidor realize buidls a cada commit e notifique os desenvolvedores de maneira clara e funcional.

* Alguns servidores oferecem o private build, que possibilita o desenvolvedor a fazer uma observação do repositório e testa-lo antes da produção, com um build mais completo.

### Com qual frequência devemos iniciar a construção do software através do servidor de integração contínua?

* Idealmente a cada commit. Isso pode ser um desafio quando temos uma frequência alta de commits. Nesse caso pode ser necessário executar os builds em paralelo.

---
