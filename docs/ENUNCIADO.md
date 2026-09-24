# Enunciado — ExpenseHub

## Cenário

Uma empresa precisa controlar solicitações de reembolso. Funcionários registram despesas, aprovadores analisam os pedidos, o setor financeiro registra pagamentos e auditores consultam todo o histórico.

O sistema deve proteger cada operação considerando:

- identidade autenticada;
- perfil do usuário;
- proprietário do reembolso;
- estado atual;
- regra de transição.

## Formato

- Trabalho individual.
- Prazo informado pelo professor: 15–20 dias.
- Entrega em repositório privado criado por **Use this template**.
- Inteligência Artificial (IA) permitida e documentada.
- Sem deploy obrigatório.
- Frontend opcional.

## Objetivo técnico

Construir uma API REST (Representational State Transfer) com:

- ASP.NET Core;
- ASP.NET Core Identity;
- Entity Framework Core;
- banco relacional;
- autenticação bearer;
- autorização por roles;
- regras de ownership no serviço;
- testes unitários.

## Entrega esperada

O repositório deve:

- compilar;
- executar conforme as instruções;
- implementar as issues do backlog central;
- possuir histórico organizado em branches e pull requests;
- possuir testes unitários significativos;
- passar pelo pipeline de qualidade;
- não conter segredos, binários ou artefatos locais;
- registrar o uso de IA em `AI-USAGE.md`.

## Fora de escopo

- deploy;
- Docker;
- anexos;
- leitura automática de comprovantes;
- integração bancária;
- múltiplas moedas;
- aprovação multinível;
- notificações;
- reabertura ou cancelamento;
- frontend obrigatório;
- testes de integração obrigatórios.

Consulte [REQUISITOS.md](REQUISITOS.md) para o contrato funcional e [RUBRICA.md](RUBRICA.md) para a pontuação.
