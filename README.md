# 🚀 Sistema de Cadastro de Empresas Parceiras

## TechConnect Solutions | Rede de Associações Comerciais

Bem-vindos ao repositório do projeto **Sistema de Cadastro de Empresas Parceiras**. Nosso objetivo é criar uma solução robusta e responsiva para a gestão de empresas parceiras.

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

### Agile: Crystal Clear
O prazo é de **6 meses**. Usamos o **Crystal Clear** para gestão ágil, focando em comunicação diária e **entregas incrementais** (**E1** a **E5**) a cada 2-3 semanas para validação direta com a Diretoria.

---

## 📅 Cronograma de Entregas (Mermaid Gantt)

Este gráfico visualiza os marcos principais e as entregas incrementais, cobrindo o prazo total de 6 meses do projeto:

<br>

```mermaid
gantt
    title MARCOS DO PROJETO (PRAZO TOTAL: 6 MESES)

    dateFormat  YYYY-MM-DD
    todayMarker off

    section Preparação e Setup (Mês 1)
    Documentação e Design :a1, 2025-01-01, 3w
    Configuração do Ambiente :a2, after a1, 1w

    section Entregas de Valor (Crystal Clear)
    Login e Autenticação (E1) :b1, after a2, 2w
    CRUD de Empresas (E2) :b2, after b1, 3w
    Upload de Logotipo (E3) :b3, after b2, 2w
    Relatórios/PDF (E4) :b4, after b3, 2w
    Painel Admin/Permissões (E5) :b5, after b4, 2w

    section Finalização (Meses 4-6)
    Testes QA e Usabilidade :c1, after b5, 1.5M
    Implantação e Entrega Final :c2, after c1, 1.5M
