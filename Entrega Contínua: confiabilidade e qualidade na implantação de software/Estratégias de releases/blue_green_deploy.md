# Blue-Green Deployment

![image](https://github.com/AndreCoutinhom/devops_and_monitoring_study/assets/91290799/401dfc3c-bb9a-4b4e-aec7-271645865277)

* O deploy já foi realizado, mas temos duas versões: uma antiga(azul) e a nova(verde) que já está em ambiente de produção.
* Entre as versões há um roteador, então em algum momento podemos modificar o fluxo para o novo ambiente, a nova versão.
* O ambiente velho (blue) fica no ar ainda um bom tempo caso algum problema surja. As conexões que existiam para o azul ficarão disponíveis até que realmente apenas a versão verde esteja totalmente funcional.

---
