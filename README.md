# Desafio de DevOps Engineer

Repositório de instrução para o desafio técnico para a vaga de Pessoa Engenheira DevOps.

## Descrição do desafio

Neste repositório, você encontrará uma aplicação web desenvolvida em [Flask](https://flask.palletsprojects.com/). Sua tarefa consiste nos seguintes passos (realizá-los na ordem que julgar adequada e ir marcando os itens completos):

- [ ] Modificar a aplicação para consumir uma variável de ambiente chamada `NAME` e, no lugar de "World", exibir o valor dessa variável.
- [ ] Modificar o arquivo `.gitignore` para que seja adequado a uma aplicação Python.
- [ ] Elaborar, implementar e reforçar um fluxo de desenvolvimento para o repositório.
- [ ] Consolidar boas práticas no repositório através de ferramentas de análise estática, hooks de pré-commit, etc. a seu critério.
- [ ] Preparar a aplicação para que seja production-ready.
- [ ] Criar arquivos e scripts para que a aplicação possa ser executada em um container.
- [ ] Elaborar um modelo de desenvolvimento que permita a execução da aplicação em um ambiente de desenvolvimento local.
- [ ] Construir pipelines de CI/CD para a aplicação utilizando GitHub Actions. Esse item possui forte relação com o fluxo de desenvolvimento, pois deve compreender o deployment em dois ambientes diferentes: homologação e produção. O deployment da aplicação deve ser realizado em um serviço serverless da Google Cloud Platform (via Terraform).
- [ ] Limitar o acesso (capacidade de fazer requisições) a ambos os ambientes (homologação e produção) por IPs / faixas de IPs.
- [ ] Documentar todo o processo, as pipelines e o fluxo de desenvolvimento do repositório, além de hospedar essa documentação em uma página do GitHub Pages.

## O que iremos avaliar

1. **Simplicidade**: A solução proposta é simples e direta? É fácil de entender e trabalhar?
2. **Organização**: A solução proposta é organizada e bem documentada? É fácil de navegar e encontrar o que se procura?
3. **Criatividade**: A solução proposta é criativa? Apresenta uma abordagem inovadora para o problema proposto?
4. **Boas práticas**: A solução proposta segue boas práticas de Python, Git, Docker, etc.?

## Atenção

- **Toda a parte de provisionamento de infraestrutura em nuvem deve ser feita usando Terraform**
- A solução desse desafio deve ser publicada em um fork deste repositório no GitHub.
- Você deve ser capaz de apresentar sua solução, explicando como a idealizou.

## Links de referência / utilidades

- [Documentação do Flask](https://flask.palletsprojects.com/en/2.3.x/)
- [Documentação do GitHub Actions](https://docs.github.com/en/actions)
- [Documentação do GitHub Pages](https://docs.github.com/en/pages)
- [Documentação do Docker](https://docs.docker.com/)
- [Documentação do Terraform](https://developer.hashicorp.com/terraform/docs)
- [Ferramentas serverless da GCP](https://cloud.google.com/serverless)
