# Build automatizado

### Etapas do build

![image](https://github.com/AndreCoutinhom/devops_and_monitoring_study/assets/91290799/ededfb26-b717-4851-9295-fd9834666cb8)

* É importante que cada uma dessas etapas possa ser executada através de forma automatizada. O build deve ser simples de executar, idealmente através de um único comando (single command build).
* Builds lentos vão afetar negativamente a integração contínua, atrasando commits e diminuindo o feedback. Otimize o build para receber feedback mais rápido.

### O que o comando faz?

* Verifique a fase de testes e analise o código;
* Verifique a ordem dessas fases;
* Verifique a infra do build system;
* Use cache;
* Use staged build/pipeline.

### Condutas recomendadas

* Uso de ferramentas de automação de build;
* Use commit-build
* Build independente de IDE;
* Tudo no repositório;
* Estrutura de diretórios bem definidos;
* Builds que falham rapidamente;
* Script único para ambientes (comando único de build)
* Use build machine.

---
