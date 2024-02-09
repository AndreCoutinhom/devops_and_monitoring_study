> *Anotações da Formação em Engenharia de Software da Alura.*

<h1 align="center">
  DevOps e monitoramento

###

![image](https://github.com/AndreCoutinhom/devops_and_monitoring_study/assets/91290799/260e3f1a-fcbc-4668-affd-c64de4869df0)

</h1>

---

Um software somente tem valor quando é entregue em ambiente de produção, para que as pessoas possam o utilizar e usufruir de seus benefícios.

Colocar um software em produção não é uma tarefa tão simples, pois envolve a utilização de diversas ferramentas para realização do deploy, principalmente em ambientes cloud hoje em dia, além de também exigir um acompanhamento contínuo, para garantir que tudo está funcionando corretamente, e, principlamente, detectar e antecipar possíveis problemas.

DevOps é a disciplina responsável por cuidar de todo esse processo de entrega e monitoramento de softwares em ambientes de produção, sendo que existem dezenas de ferramentas para realizar tais tarefas.

## O que é DevOps? 🎥

Uma cultura baseada em fatores de desenvolvimento e operações em software. Busca o equilíbrio entre estabilidade dos serviços e performance de grandes softwares.

![image](https://github.com/AndreCoutinhom/devops_and_monitoring_study/assets/91290799/68bdc1f4-e7f1-4dc0-805a-ea5ad2088387)

### Formas de abordar a cultura DevOps:

* Colaboração;
* Qualidade;
* Agilidade;
* Segurança;
* Containerização;
* Infraestrutura;
* Entrega contínua;
* Monitoramento e análise.

---

## [Devops: o que é e principais práticas](https://www.alura.com.br/artigos/devops-o-que-e?_gl=1*hjtpq5*_ga*ODM1Nzk2OTUyLjE2OTgzNDc1Mjk.*_ga_1EPWSW3PCS*MTcwNjM4MDE0OS4xNzEuMS4xNzA2Mzg2NDI3LjAuMC4w*_fplc*MDB1bHp5ZU9nTzc0OEFOcHZKOU44dzFNNEkxM0hQJTJGR2R6VlN6UCUyQjAzcU1rVVRNVEVQNzVtQXdOc1g1c3VkMVZEaUNiTlVBa3FCdVhoQkl1d3ZzRGtvMnJsSlJQVTE4UmxLbWRrZjVIR0tlTVFaWWM4ZjJWclhhMG43UHYxQSUzRCUzRA..) 📕
![image](https://github.com/AndreCoutinhom/devops_and_monitoring_study/assets/91290799/073bfe9b-9f56-4862-b568-c762db79d416)

---

## [Primeiros passos com Devops – Hipsters #81](https://cursos.alura.com.br/extra/hipsterstech/primeiros-passos-com-devops-hipsters-81-a505) 🎧

---

## O que é DevSecOps? 🎥

O processo levantado pela cultura DevOps regido por condutas de cibersegurança.

![image](https://github.com/AndreCoutinhom/devops_and_monitoring_study/assets/91290799/e8a15985-7012-4446-b958-271c15add295)

### Pilares:

* Segurança em primeiro lugar;
* Velocidade;
* Entrega contínua;
* Confiabilidade.

> É melhor que seja seguro e lento do que rápido e inseguro.

> Você nunca pode ter segurança demais em suas aplicações.
> O que puder utilizar de ferramentas para automatizar processos de segurança, use.

Assim como no exemplo abaixo, a auditoria com processos de segurança precisam ser verificados logo após a compilação do código.

![image](https://github.com/AndreCoutinhom/devops_and_monitoring_study/assets/91290799/c347acb8-6eb5-4d28-ae28-af91ab2cb185)

### Ferramentas:

* GitLab CI / GitHub Actions;
* Circle CI;
* Jenkins;
* CodePipeline.

---

## [DevOps: Observabilidade – Hipsters Ponto Tech #260](https://cursos.alura.com.br/extra/hipsterstech/devops-observabilidade-hipsters-ponto-tech-260-a1052) 🎧

---

## SRE - Engenharia de Confiabilidade de Sites 🎥

Criada pela Google para identificar níveis de confiabilidade em desenvolvimento e infraestruturas. O SRE leva as equipes de desenvolvimento às práticas de observabilidade utilizando métricas e atribuição de dados para comparação de versões. Utilizando o SRE é possível reduzir o tempo de resposta a um incidente.

![image](https://github.com/AndreCoutinhom/devops_and_monitoring_study/assets/91290799/bfbac934-8a0f-49bf-8f3f-dfa72d135ee0)

![image](https://github.com/AndreCoutinhom/devops_and_monitoring_study/assets/91290799/3024a6bf-aa24-4398-af47-24a7fd794b0d)

### Chaos engineering 

Consiste em falhar no ambiente para verificar o quanto essa falha interfere no sistema, dessa forma avaliar sua resiliência.

---

## [SRE: Site Reliability Engineering – Hipsters #187](https://cursos.alura.com.br/extra/hipsterstech/sre-site-reliability-engineering-hipsters-187-a374) 🎧

---

## O que é Observabilidade? 🎥

### Pilares

* Métricas;
* Traços Distribuídos;
* Logs.

#### Métricas

[Prometheus](https://prometheus.io) e [Grafana](https://grafana.com) são algumas das principais ferramentas open-source para monitoramento de sistema de database. Permitem a observabilidade dos dados do software desenvolvido.

![image](https://github.com/AndreCoutinhom/devops_and_monitoring_study/assets/91290799/251a6210-575b-4792-9ee8-96470aaffe30)

![image](https://github.com/AndreCoutinhom/devops_and_monitoring_study/assets/91290799/a60c1215-3249-4624-ad9e-54eddb17b6f8)

#### Traços distribuídos

[Jaeger](https://www.jaegertracing.io) é uma ferramenta que permite a observabilidade das comunicações entre os microsserviços. Outras opções de ferramenta são Service Mesh e Proxy.

![image](https://github.com/AndreCoutinhom/devops_and_monitoring_study/assets/91290799/67f0bafe-09b7-4869-8c3a-da564197a5e9)

#### Logs

Log de dados é uma expressão utilizada para descrever o processo de registro de eventos relevantes num sistema computacional. Esse registro pode ser utilizado para restabelecer o estado original de um sistema ou para que um administrador conheça o seu comportamento no passado. 

É geralmente programado em Java, através de Sidecar, instalação no Host ou Shell script. Pode ser vizualizado em ferramentas como [Graylog](https://graylog.org).

![image](https://github.com/AndreCoutinhom/devops_and_monitoring_study/assets/91290799/ee2a0da5-2eef-499a-b31c-4d72ed407688)

---

## Monitorando aplicações: 4 Golden Signals 🎥

### O quatro sinais de ouro para monitoramento

* Latência - Quanto tempo uma determinada requisição demora para ser executada?
* Erros - O quão bem o cliente consegue utilizar o produto sem interrupções de sistema?
* Tráfego - O quão otimizado meu produto é em relação a volume de dados?
* Saturação - Qual o limite que meu produto consegue alcançar? O que posso fazer caso ele alcance esse limite?

---

## Monitoramento com [Netdata](https://www.netdata.cloud) 🎥

![image](https://github.com/AndreCoutinhom/devops_and_monitoring_study/assets/91290799/993ebd4f-7b17-4b3d-ac7a-bfe20a43371e)

Netdata é uma ferramenta de monitoramento open-source que pode se comunicar com outras ferramentas.

Ele oferece um overview da aplicação quando instalado, apresentando métricas e gráficos sobre comportamento de rede, buffers, performance, consumo de memória, especificações de hardware e praticamente tudo em relação a monitoramento.

O Netdata também possui uma configuração de alarmes. Se algo sai dos eixos da aplicação (seja por latência, erro, tráfego ou saturação), isso é comunicado pelo Netdata e até pode ser compartilhado em plataformas empresariais como o [Slack](https://slack.com/intl/pt-br).

---

## [Monitoramento: não receba mais telefonemas de madrugada! – Hipsters #12](https://cursos.alura.com.br/extra/hipsterstech/monitoramento-nao-receba-mais-telefonemas-de-madrugada-hipsters-12-a574) 🎧

---

## O que são Containers? 🎥

Os containers são uma forma de gerenciar processamento computacional entre diferentes contextos funcionais. Em outras palavras, são unidades executáveis de software em que o código do aplicativo é empacotado com suas respectivas bibliotecas e dependências, usando métodos comuns para executá-los em qualquer lugar, seja em um computador desktop, na estrutura de TI tradicional ou na cloud.

![image](https://github.com/AndreCoutinhom/devops_and_monitoring_study/assets/91290799/8349bd71-543c-42db-a981-da63927f68ff)

Os containers eliminam a necessidade de cada aplicação possuir um novo sistema operacional, algo que não é alcançável com sistemas distribuídos e máquinas virtuais.

São mais leves, menos custosos em manutenção (um único SO) e mais rápidos para provisionar.

---

## O que é Serverless? 🎥

Serverless é o paradigma de executar código sem se preocupar com servidores. Ao contrário do que o nome sugere, os servidores ainda existem, mas são executados por um provedor.

Os principais provedores de servidor são a AWS, a Azure e a Google; todos através de computação na nuvem.

### Prós

* Paga pelo que usa;
* Cada função em linguagem diferente;
* Arquiteturas orientadas a eventos;
* Auto-escalável.

### Contras

* Duração de execução;
* Vendor Lock-In (configurações e funcionamento presos aos serviços do provedor);
* Difícil de debugar;
* Ambiente de execução de difícil controle.

### Componentes (AWS)

* Lambda;
* API Gateway;
* SQS;
* DynamoDB;
* SNS;
* S3.

---

## O que é Infraestrutura como Código (IaC)? 🎥

Infraestrutura como código é um processo de gerenciamento de infraestrutura de TI que aplica as práticas recomendadas do desenvolvimento de software DevOps ao gerenciamento de recursos de infraestrutura de nuvem. Através de métodos como virtualização e automação, é possível desenvolver um sistema mais ágil, menos custoso e muito mais fácil de monitorar.

---
