# Projeto de Estudo: GitFlow com Login e Dashboard

Este é um projeto de estudo prático focado em aplicar o fluxo de trabalho **GitFlow** em um ambiente de desenvolvimento web front-end. O objetivo principal foi versionar cada etapa da criação de uma aplicação simples, que inclui telas de login, cadastro e um painel principal, utilizando HTML, CSS e JavaScript.

## 🚀 Sobre o Projeto

O cenário proposto foi o desenvolvimento de uma página de login com tema escuro, validação de campos via JavaScript e, principalmente, um controle de versões robusto seguindo as boas práticas do mercado. A aplicação exibe mensagens de erro e sucesso de acordo com a interação do usuário.

## ✨ Funcionalidades

-   **Tela de Login:** Interface para autenticação do usuário.
-   **Validação de Campos:** O JavaScript verifica se os campos estão vazios e valida as credenciais (`usuário: adm`, `senha: 123`).
-   **Mensagens de Feedback:** Exibe mensagens dinâmicas para o usuário ("Preencha todos os campos!", "Login realizado com sucesso!").
-   **Tela de Cadastro:** Formulário para registro de novos usuários.
-   **Painel Principal (Dashboard):** Tela exibida após o login bem-sucedido.
-   **Estrutura de Versionamento GitFlow:** Utilização de branches específicas para cada funcionalidade, correção e release.

## 🛠️ Tecnologias Utilizadas

-   HTML5
-   CSS3
-   JavaScript
-   Git
-   GitHub

## 🌿 Fluxo de Versionamento (GitFlow)

O principal foco do projeto foi a simulação de um ambiente de desenvolvimento real utilizando o GitFlow. As branches `main` (produção) e `develop` (desenvolvimento) foram a base para o trabalho.

A tabela abaixo resume as branches criadas e suas finalidades:

| Tipo de Branch | Nome                        | Base    | Finalidade                                            |
| :------------- | :-------------------------- | :------ | :---------------------------------------------------- |
| **Feature** | `feature/dashboard`         | develop | Criar o painel principal do site após o login.        |
| **Feature** | `feature/cadastro-usuario`  | develop | Implementar o formulário de cadastro de novos usuários. |
| **Hotfix** | `hotfix/erro-html`          | main    | Corrigir um erro estrutural no HTML da página de login. |
| **Release** | `release/v1.1.0`            | develop | Preparar a nova versão do sistema para publicação.      |

## ⚙️ Como Executar

1.  Clone o repositório para sua máquina local:
    ```bash
    git clone [https://github.com/PeedrooGabriel/atividade-avaliativa.git](https://github.com/PeedrooGabriel/atividade-avaliativa.git)
    ```
2.  Navegue até a pasta do projeto:
    ```bash
    cd atividade-avaliativa
    ```
3.  Abra o arquivo `index.html` no seu navegador de preferência.

---

Desenvolvido por **Pedro Gabriel** como parte de uma atividade de avaliação.
