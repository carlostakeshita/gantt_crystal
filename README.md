# 🚀 Sistema de Cadastro de Empresas Parceiras

## TechConnect Solutions | Rede de Associações Comerciais

Bem-vindos ao repositório do projeto **Sistema de Cadastro de Empresas Parceiras**. Este sistema visa otimizar a gestão de empresas parceiras com foco em segurança, responsividade e entregas incrementais.

---

## ✨ Requisitos Chave

O sistema deve incluir:

* **Login Seguro:** Autenticação de usuários e recuperação de senha.
* **Gestão (CRUD):** Módulos completos para Cadastro, Edição, Exclusão e Listagem de empresas.
* **Mídia:** Upload e armazenamento seguro de **logotipos**.
* **Relatórios:** Exportação da lista de empresas em **PDF** e **Excel**.
* **Administração:** Painel com controle de **permissões de acesso**.
* **Acessibilidade:** Interface **responsiva** (desktop e mobile).
* **Tecnologia:** Banco de dados **MySQL**.

---

## 👥 Equipe e Metodologia

| Função | Membro da Equipe |
| :--- | :--- |
| **Gerente de Projetos** | (Nome do Gerente) |
| **Analista de Sistemas** | (Nome do Analista) |
| **Desenvolvedores (2)** | (Nomes dos Devs) |
| **Designer (UI/UX)** | (Nome do Designer) |
| **Tester (QA)** | (Nome do Tester) |

###  agile: Crystal Clear
O prazo é de **6 meses**. Usamos o **Crystal Clear** para gestão ágil, garantindo comunicação diária e entregas **incrementais** a cada 2-3 semanas para validação da Diretoria.

---

## 📅 Cronograma de Entregas (Mermaid Gantt)

Este gráfico visualiza as principais entregas parciais do projeto, alinhadas às nossas validações ágeis (as semanas são estimativas de entrega):

<br>

```mermaid
gantt
    title Cronograma de Entregas - Crystal Clear (Prazo Total: 6 Meses)

    dateFormat  YYYY-MM-DD

    section Setup e Design
    Documentação Funcional      :doc, 2025-01-01, 2w
    Setup Ambiente/BD           :setup, after doc, 1w

    section Entregas Incrementais (Validação com Cliente)
    E1: Módulo de Login (Semana 3)  :e1, after setup, 2w
    E2: CRUD de Empresas (Semana 6) :e2, after e1, 3w
    E3: Upload de Logotipo (Semana 8) :e3, after e2, 2w
    E4: Relatórios PDF/Excel (Semana 10) :e4, after e3, 2w
    E5: Painel Admin/Permissões (Semana 12) :e5, after e4, 2w

    section Finalização
    Testes QA e Usabilidade     :qa, after e5, 6w
    Implantação e Entrega Final :impl, after qa, 4w
