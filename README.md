# 💊 Plataforma de Farmácia Virtual - Arquitetura AWS

Este repositório contém o projeto de arquitetura de nuvem para uma farmácia virtual fictícia, desenvolvido como desafio prático para o curso da DIO. O foco principal é a utilização dos serviços da Amazon Web Services (AWS) para garantir segurança, escalabilidade e resiliência.

## 🎯 Objetivo do Projeto
Conceber uma infraestrutura capaz de suportar uma operação de e-commerce farmacêutico, lidando com picos de tráfego, armazenamento seguro de receitas médicas e gestão rigorosa de acesso a dados sensíveis.

## 🏗️ Arquitetura da Solução
A infraestrutura foi desenhada utilizando os seguintes pilares da AWS:

* **Amazon EC2**: Hospedagem da aplicação (frontend e backend), garantindo que o site esteja sempre disponível para os clientes.
* **Amazon RDS (MySQL)**: Banco de dados gerenciado para controle de estoque, registro de clientes e histórico de pedidos.
* **Amazon S3**: Armazenamento seguro de objetos, utilizado para fotos de produtos e imagens de prescrições médicas.
* **AWS IAM**: Controle de identidade e acesso para garantir que cada colaborador acesse apenas o necessário para sua função.



## 📄 Relatório Técnico
O detalhamento completo da implementação e as justificativas para a escolha de cada serviço podem ser encontrados no arquivo:
👉 [modelo-relatorio.md](./modelo-relatorio.md)

## 🚀 Como visualizar
1. Navegue pelos arquivos do repositório.
2. Leia o relatório técnico para entender as decisões de design.
3. Sinta-se à vontade para propor melhorias via Pull Requests!
