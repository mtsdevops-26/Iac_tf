# Iac_tf

#Resumo do projeto
Primeiro projeto de Infraestrutura como código com docker, utilizando Terraform para provisionamento e AWS como provedor da infraestrutura.

hammer Funcionalidades do projeto
A partir desse projeto você pode:

Criar ambientes para aplicações Docker

Separar o seu código em múltiplos ambientes, dependendo das necessidades

Criar módulos para acelerar o desenvolvimento no Terraform

heavy_check_mark Técnicas e tecnologias utilizadas
Neste App são exploradas as seguintes técnicas e tecnologias:

Criação de maquinas para executar containers Docker: criação de maquinas de forma automática pelo ECS (Elastic Container Service) da AWS feito de forma automática pelo Fargate

Utilização de módulos: Utilização dos módulos do Terraform, desenvolvidos pelos provedores e comunidade

Elastic Constainer Registry: o repositório de containers da AWS, onde vamos colocar as nossas imagens.

Separação de ambientes: 2 ambientes separados, construídos de forma automática pelo Terraform, reutilizando código.

#Abrir e rodar o projeto
O projeto foi desenvolvido no VSC (Visual Studio Code), sendo assim, instale o VSC (pode ser uma versão mais recente) e, na tela inicial, procure a opção extensões, ou aperte Ctrl+Shift+X, e busque por HashiCorp Terraform, assim teremos o suporte do intellisense, tornando o trabalho de escrever o código mais rápido.

Caso baixou o zip, extraia o projeto antes de procurá-lo, pois não é possível abrir via arquivo zip

Vá até a paste a abra a pasta do projeto. Após abrir o projeto abra um terminal, pode ser o integrado com o VSC, navegue até a pasta env/Prod e execute o comando terraform init dentro dela, agora temos o Terraform iniciado e podemos começar a utilizá-lo. Para criar a infraestrutura, execute o terraform apply na pastas de Produção (env/Prod).

