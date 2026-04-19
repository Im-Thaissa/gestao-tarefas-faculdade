# Documentação do Sistema

## 1) Visão Geral e Arquitetura do Sistema
Este sistema é uma ferramenta de gerenciamento de tarefas que auxilia os usuários a organizarem suas atividades acadêmicas de forma eficiente. A arquitetura do sistema é baseada em uma estrutura de microserviços que permite a escalabilidade e manutenção ágil, utilizando tecnologias como Node.js para o backend e React para o frontend.

## 2) Histórico Completo de Mudanças
- 
2026-04-19  
  - Adição do módulo de autenticação.
  - Melhoria na interface do usuário.
- 2026-02-10  
  - Refatoração do código do backend.
  - Implementação de novos endpoints API.

## 3) Diagrama BPMN para Fluxo de Gerenciamento de Tarefas
![BPMN Diagram](link_do_diagrama)

## 4) Descrições Detalhadas dos Componentes
- **Backend:** Responsável pela lógica de negócios e interação com o banco de dados. 
- **Frontend:** Interface do usuário que permite interação e visualização de dados.

## 5) Documentação dos Endpoints da API com Exemplos
- `GET /tarefas`
  - **Descrição:** Obtém todas as tarefas.
  - **Exemplo de Resposta:** 
    ```json
    [{"id":1,"titulo":"Estudar para prova","status":"pendente"}]
    ```

## 6) Esquema do Banco de Dados
![Diagrama do Banco de Dados](link_do_diagrama)

## 7) Estrutura do Frontend
```
/ 
├── src/
│   ├── components/
│   ├── pages/
│   └── App.js
└── public/
```

## 8) Instruções de Configuração e Execução
1) Clone o repositório: `git clone https://github.com/Im-Thaissa/gestao-tarefas-faculdade.git`
2) Instale as dependências: `npm install`
3) Execute o aplicativo: `npm start`

## 9) Checklist de Conformidade de Requisitos
| Requisito                      | Status    |
|--------------------------------|-----------|
| Autenticação de usuário        | Cumprido  |
| Gerenciamento de tarefas       | Cumprido  |
| Interface responsiva           | Cumprido  |
| Relatório de tarefas           | Pendente  |