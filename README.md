# gantt_crystal

gantt
    dateFormat  YYYY-MM-DD
    title Entregas Incrementais - Método Crystal Clear

    section Preparações Iniciais
    Configuração do Ambiente  :c1, 2025-01-01, 1w
    Modelagem do Banco de Dados :c2, after c1, 1w
    Layout UI/UX              :c3, after c1, 2w

    section Entrega 1 (Semana 3)
    Módulo de Login             :e1, after c2, 1w
    Revisão da Diretoria (E1)   :after e1, 1d

    section Entrega 2 (Semana 6)
    CRUD de Empresas            :e2, after e1, 3w
    Revisão da Diretoria (E2)   :after e2, 1d

    section Entrega 3 (Semana 8)
    Upload de Logotipo          :e3, after e2, 2w
    Revisão da Diretoria (E3)   :after e3, 1d

    section Entrega 4 (Semana 10)
    Desenvolvimento de Relatórios :e4, after e3, 2w
    Revisão da Diretoria (E4)   :after e4, 1d

    section Entrega 5 (Semana 12)
    Painel Admin/Permissões     :e5, after e4, 2w
    Revisão da Diretoria (E5)   :after e5, 1d

    section Finalização (Mês 6)
    Testes QA e Usabilidade     :t1, after e5, 6w
    Implantação Final           :i1, after t1, 4w
