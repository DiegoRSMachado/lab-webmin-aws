# Laboratório: Implementação de Webmin na AWS EC2

> **Projeto Prático de Segurança da Informação & Administração de Sistemas**
> *SENAC-DF | Tópicos Avançados*

## 📌 Sobre o Projeto
Este laboratório documenta a implementação de uma infraestrutura de gerenciamento de servidores Linux utilizando a nuvem **Amazon AWS (EC2)** e o painel administrativo **Webmin**. O objetivo foi estabelecer um ambiente seguro e visual para monitoramento e configuração de servidores, aplicando boas práticas de segurança de rede e controle de acesso.

## 🛠️ Tecnologias Utilizadas
* **Nuvem:** Amazon AWS (EC2 Instance)
* **Sistema Operacional:** Ubuntu Server / Linux
* **Ferramenta de Gestão:** Webmin (Porta 10000)
* **Segurança:** AWS Security Groups & Criptografia SSH

## 🚀 Principais Configurações Realizadas
1.  **Hardening de Rede:** Configuração de *Security Groups* na AWS para permitir tráfego controlado na porta TCP 10000.
2.  **Instalação Segura:** Deploy do Webmin via repositório oficial com validação de chaves GPG.
3.  **Controle de Acesso:** Implementação de autenticação manual para bypass das restrições de chave `.pem` da AWS e criação de usuários administrativos dedicados (PoLP).
4.  **Monitoramento:** Configuração de Dashboard para análise em tempo real de CPU, Memória e Processos.

## 📄 Documentação Completa
O relatório técnico detalhado, contendo todos os prints, passos de execução e justificativas teóricas, está disponível no arquivo PDF neste repositório.

👉 **[Clique aqui para visualizar o Relatório Técnico (PDF)](Relatorio_Tecnico_Webmin_AWS.pdf)**

---
*Autor: Diego Machado*
*Brasília, 2025*
