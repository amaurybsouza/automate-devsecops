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
- [Alice and Bob Learn Application Security](https://www.amazon.com.br/Alice-Bob-Learn-Application-Security/dp/1119687357/ref=tmm_pap_swatch_0#averageCustomerReviewsAnchor).
- [Alice and Bob Learn Secure Coding](https://www.amazon.com.br/Alice-Bob-Learn-Secure-Coding/dp/1394171706/ref=pd_bxgy_thbs_d_sccl_1/133-7210045-6726819?pd_rd_w=dZllK&content-id=amzn1.sym.ea5263f5-901f-4a74-9b73-3fc0e530788d&pf_rd_p=ea5263f5-901f-4a74-9b73-3fc0e530788d&pf_rd_r=42R8W831PCXY7HMCM0BV&pd_rd_wg=b11TK&pd_rd_r=e61aa667-0659-469a-b7a0-7f687cd26f91&pd_rd_i=1394171706&psc=1).

# DevSecOps Tools
Este conjunto de ferramentas é útil para estabelecer uma plataforma DevSecOps. Dividimos as ferramentas em diversas categorias que auxiliam nas diferentes áreas do DevSecOps.

## Secret Management
Para dar suporte à segurança como código, credenciais e segredos confidenciais precisam ser gerenciados, protegidos, mantidos e rotacionados usando automação.- [TruffleHog](https://github.com/trufflesecurity/trufflehog)
- [Vault](https://www.hashicorp.com/pt/products/vault)
- [Conjur](https://www.conjur.org/use-cases/ci-cd-pipelines/)

## Continuous Integration & Delivery
Integração Contínua/Implantação Contínua (CI/CD) é um método para entregar aplicativos com frequência aos clientes, introduzindo automação nas etapas de desenvolvimento. CI/CD é uma solução para os problemas que a integração de novo código pode causar às equipes de desenvolvimento e operações.
- [GitLab](https://about.gitlab.com) 
- [Jenkins](http://jenkins-ci.org/)
- [Travis-CI](https://www.travis-ci.com/)
- [Argo](https://argoproj.github.io/)

## Source Code Management
Inclui também alguns provedores de código fonte que são muito utilizados no mercado como um todo.
- [GitHub](https://github.com/)
- [GitLab](https://about.gitlab.com)
- [BitBucket](https://bitbucket.org/product/)

## SCA
Descubra algumas ferramentas DevSecOps para segurança de aplicativos com recursos como varredura de dependências de código aberto, monitoramento em tempo real e correção de vulnerabilidades.
- [Snyk](https://snyk.io/pt-BR/)
- [Dependency-Check](https://github-com.translate.goog/dependency-check/DependencyCheck?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt&_x_tr_pto=tc)
- [Dependency-Track](https://github.com/DependencyTrack/dependency-track)

## SAST
sasasas
- [SonarQube](https://www.sonarsource.com/open-source-editions/sonarqube-community-edition/).
- [Checkov](https://github.com/bridgecrewio/checkov) - Com foco em IaC, evite configurações incorretas na nuvem e encontre vulnerabilidades durante o tempo de construção em infraestrutura como código, imagens de contêiner e pacotes de código aberto.