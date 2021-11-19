Ce repository contient les éléments liées à la session "Power Virtual Agents & Multiples environnements : comment faire grâce à Azure DevOps" que j'ai donnée lors du Power Platform French Summit 2021 :

![OnePager](.\Illustration\2021-11-19 - PVA et DevOps - OnePager.png)



Le repository contient :

- les pipelines YAML pour Azure DevOps
  - [azure-pipelines-1-save.yml](.\[Azure_Pipelines]\azure-pipelines-1-save.yml), qui permet de récupérer une solution Power Apps et stocker les éléments dans un repository en ayant remplacé certaines informations par des placeholders
  - [azure-pipelines-2-deploy.yml](.\[Azure_Pipelines]\azure-pipelines-2-deploy.yml), qui permet de déployer une solution Power Apps à partir du repository, en remplaçant les placeholders par des valeurs passées en variables du pipeline
- le support présenté pendant l'événement : [2021-11-19 - PVA et DevOps - Présentation.pdf](.\Présentation\2021-11-19 - PVA et DevOps - Présentation.pdf)