# gantt_crystal

# 🚀 Sistema de Cadastro de Empresas Parceiras - Rede de Associações Comerciais

Bem-vindos ao repositório do projeto **Sistema de Cadastro de Empresas Parceiras**, desenvolvido pela **TechConnect Solutions** para a Rede de Associações Comerciais.

Este documento detalha o escopo, a equipe, a metodologia e o cronograma de entregas do projeto.

---

## 💡 Sobre o Projeto

O objetivo principal é desenvolver um sistema robusto e seguro para o cadastro, gerenciamento e consulta das empresas parceiras da rede de associações. O sistema visa otimizar a organização das informações e facilitar a administração dos dados.

### 📋 Requisitos Funcionais

O sistema contemplará as seguintes funcionalidades:

* **Área de Login e Autenticação:** Acesso seguro com autenticação de usuários e funcionalidade de recuperação de senha.
* **Gestão de Empresas (CRUD):** Módulos completos para **C**adastrar, **R**elacionar (Listar), **U**pdate (Editar) e **D**elete (Excluir) empresas parceiras.
* **Upload de Logotipos:** Funcionalidade para armazenar com segurança o logotipo de cada empresa no servidor.
* **Relatórios:** Geração de relatórios básicos da lista de empresas ativas nos formatos **PDF** e **Excel**.
* **Painel Administrativo:** Interface de gestão com **controle de permissões** para diferentes perfis de usuários.
* **Design Responsivo:** Interface otimizada e acessível via **desktop** e **dispositivos móveis**.
* **Banco de Dados Integrado:** Armazenamento seguro e consistente das informações.

---

## 👥 Equipe do Projeto

A equipe designada pela TechConnect Solutions é composta por:

| Função | Membro da Equipe | Responsabilidades Chave |
| :--- | :--- | :--- |
| **Gerente de Projetos** | (Nome do Gerente) | Planejamento, Acompanhamento (Gantt/Crystal Clear), Comunicação com o Cliente. |
| **Analista de Sistemas** | (Nome do Analista) | Levantamento de Requisitos e Documentação Funcional. |
| **Desenvolvedor 1** | (Nome do Desenvolvedor) | Programação Back-end e Integrações. |
| **Desenvolvedor 2** | (Nome do Desenvolvedor) | Programação Front-end e Desenvolvimento de Relatórios. |
| **Designer de Interface (UI/UX)** | (Nome do Designer) | Rascunho, Layout Definitivo e Design Responsivo. |
| **Tester (QA)** | (Nome do Tester) | Testes Unitários, de Integração e de Usabilidade. |

---

## 🗓️ Cronograma e Metodologia

O projeto tem um **prazo de entrega de 6 meses**.

### 🛠️ Metodologia e Acompanhamento

O projeto será gerenciado combinando duas abordagens:

1.  **Gráfico de Gantt:** Para o planejamento visual macro, garantindo a organização das atividades, a sequência e a duração.
2.  **Método Ágil Crystal Clear:** Priorizando **comunicação diária rápida** e a **entrega incremental** de valor ao cliente. A diretoria será envolvida a cada entrega parcial para revisão e validação.

### 📦 Entregas Incrementais (Crystal Clear)

As entregas parciais e seu cronograma visual são:

| Entrega | Foco da Funcionalidade | Prazo Estimado | Ação do Cliente/Diretoria |
| :--- | :--- | :--- | :--- |
| **Entrega 1** | Módulo de Login e Autenticação | **Semana 3** | Revisão e Validação do Acesso. |
| **Entrega 2** | CRUD de Empresas (Completo) | **Semana 6** | Revisão da Gestão básica dos dados. |
| **Entrega 3** | Upload de Logotipo Integrado | **Semana 8** | Validação do armazenamento de imagens. |
| **Entrega 4** | Geração de Relatórios (PDF/Excel) | **Semana 10** | Validação da exportação de dados. |
| **Entrega 5** | Painel Administrativo e Permissões | **Semana 12** | Validação do Controle de Acesso. |
| **Entrega Final** | Sistema Testado e Implantado | **Mês 6** | Validação Final e Aceite do Sistema. |

<br>

### 📈 Cronograma Visual (Mermaid Gantt)

```mermaid
gantt
    title Cronograma de Entregas - Crystal Clear (Prazo de 6 Meses)

    dateFormat  YYYY-MM-DD

    section Pré-Desenvolvimento
    Documentação Funcional      :doc, 2025-01-01, 2w
    Design de Interface (UI/UX) :ui, after doc, 2w
    Setup e Banco de Dados      :setup, after doc, 1w

    section Entrega 1 (Semana 3)
    Módulo de Login             :e1, after setup, 2w

    section Entrega 2 (Semana 6)
    CRUD de Empresas            :e2, after e1, 3w

    section Entrega 3 (Semana 8)
    Upload de Logotipo          :e3, after e2, 2w

    section Entrega 4 (Semana 10)
    Geração de Relatórios (PDF/Excel) :e4, after e3, 2w

    section Entrega 5 (Semana 12)
    Painel Administrativo/Permissões  :e5, after e4, 2w

    section Finalização (Mês 6)
    Testes QA e Usabilidade     :qa, after e5, 6w
    Implantação e Entrega Final :impl, after qa, 4w
