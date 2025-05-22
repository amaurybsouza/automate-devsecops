# Awesome DevSecOps   [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Inspirado pela trend "awesome-*" no GitHub. Esta é uma coleção de documentos, apresentações, vídeos, materiais de treinamento, ferramentas, serviços e liderança geral que apoiam a missão do DevSecOps. Estes são os blocos de construção e informações essenciais que podem ajudá-lo a organizar um experimento DevSecOps ou a desenvolver seu próprio programa DevSecOps.

Esta lista não será totalmente abrangente e mudará conforme o DevSecOps amadurece. Pretendo que seja uma lista incrível que cresça e mude à medida que a comunidade aprende e aprimora a forma como o DevSecOps é implementado e adotado. Para serem incluídos nesta lista, as informações, ferramentas, fornecedores ou iniciativas devem fornecer recursos gratuitos ou de código aberto que auxiliem na missão DevSecOps. 

![image.png](https://github.com/amaurybsouza/automate-devsecops/blob/main/images/image.png)

## Manifesto
Abaixo o trecho do [manisfesto de DevSecops](https://www.devsecops.org/), onde é compartilhado os pontos que fazem da abordagem uma cultura de apŕoximar a segurança sempre na fase de desenvolvimento de software (SDLC). Peço por gentileza que você leie e aplique no seu dia a dia esse pensamento.

> Through Security as Code, we have and will learn that there is simply a better way for security practitioners, like us, to operate and contribute value with less friction. We know we must adapt our ways quickly and foster innovation to ensure data security and privacy issues are not left behind because we were too slow to change.

## Presentations
Many talks are now targeting the change of adding Security into the DevOps environment. I would like to share some of the most expressive talks.

- [DevSecOps: Integrating Security in the Development Pipeline](https://www.youtube.com/watch?v=Rtk5zDiPzpA).
- [Definindo sua pipeline de CI/CD no GitLab com o poderoso Checkov integrado ao Terraform - Amaury](https://www.youtube.com/watch?v=9QVWHMEdR4U&t=14s).
- [Introdução Prática ao OWASP DevSecOps Guideline](https://www.youtube.com/watch?v=fLdNYmI7oAc).
- [DevSecOps - Introdução ao Desenvolvimento Seguro - Joas Antonio dos Santos](https://www.youtube.com/watch?v=GXpDn4AwveM).
- [DevSecOps: O Caminho da Segurança Ágil | Daniel Melo](https://www.youtube.com/watch?v=mod7ip-rkHY).
- [KCD Brasil](https://www.youtube.com/@KCD_Brazil)
- [OWASP Dependency-Check: analisando vulnerabilidades em packages e bibliotecas de suas aplicações](https://www.youtube.com/watch?v=zna1gDpKOCo)

## Courses
Listando alguns cursos que eu peguei e são ótimos para você começar na jornada de DevSecOps.
- [DevSeOps Fundamentals](https://www.udemy.com/course/devsecops-fundamentals/learn/lecture/32105618#overview).
- [DevOps Foundations: DevSecOps](https://www.linkedin.com/learning/devops-foundations-devsecops-17416896).
- [Roadmap DevSecops](https://roadmap.sh/r/devsecops-88a05).
- [DevSecOps com GitHub Actions](https://www.udemy.com/course/devsecops-com-github-actions/learn/lecture/48433533#overview).
- [DevSecOps Tutorial for Beginners | CI Pipeline with GitHub Actions and Docker Scout](https://www.youtube.com/watch?v=gLJdrXPn0ns).
- [Web App Vulnerabilities - DevSecOps Course for Beginners](https://www.youtube.com/watch?v=F5KJVuii0Yw).

## Books
Alguns livros que eu gostei e ler e que agregaram muito no meu aprendizado e que pode ajudar você na mesma pegada da ideia de DevSecOps.
- [DevOpsSec](https://www.oreilly.com/library/view/devopssec/9781491971413/).
- [Docker Security](https://binarymist.io/publication/docker-security/).
- [Securing DevOps](https://www.manning.com/books/securing-devops?a_aid=securingdevops&a_bid=1353bcd8).
- [The DevOps Handbook](https://www.oreilly.com/library/view/the-devops-handbook/9781457191381/).

# DevSecOps Tools
This collection of tools are useful in establishing a DevSecOps platform. We have divided the tools into several categories that help with the different divisions of DevSecOps.

## Secret Management
To support security as code, sensitive credentials and secrets need to be managed, security, maintained and rotated using automation. 
- [TruffleHog](https://github.com/trufflesecurity/trufflehog)
- [Vault](https://www.hashicorp.com/pt/products/vault)
- [Conjur](https://www.conjur.org/use-cases/ci-cd-pipelines/)

## Continuous Integration & Delivery
Continuous Integration / Continuous Deployment (CI/CD) is a method to frequently deliver apps to customers by introducing automation into the stages of app development. CI/CD is a solution to the problems integrating new code can cause for development and operations teams.
- [GitLab](https://about.gitlab.com) 
- [Jenkins](http://jenkins-ci.org/)

## SCA
Discover some DevSecOps tools for application security with features like open source dependency scanning, real-time monitoring, and vulnerability remediation.

- [Snyk](https://snyk.io/pt-BR/)
- [Dependency-Check](https://github-com.translate.goog/dependency-check/DependencyCheck?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt&_x_tr_pto=tc)
- [Dependency-Track](https://github.com/DependencyTrack/dependency-track)