# Arquitetura e Decisões Técnicas — PsiGestão

## 1. Visão Geral da Solução
O **PsiGestão** é uma aplicação Web desenvolvida para operar em ambiente de nuvem, atendendo à Secretaria Municipal de Saúde.

## 2. Pilha Tecnológica (Tech Stack)
- **Interface (Frontend):** React.js / TypeScript
- **Servidor (Backend):** Node.js / Python
- **Banco de Dados:** PostgreSQL / MySQL
- **Controle de Versão:** Git & GitHub
- **Hospedagem:** Vercel / Render

## 3. Entidades Principais do Banco de Dados
- **Usuários:** (Id, Nome, Email, Senha, Perfil: Admin/Psicólogo/Recepção)
- **Pacientes:** (Id, Nome, CPF, CartãoSUS, Telefone, DataNascimento, NomeResponsavel)
- **Agendamentos:** (Id, DataHora, PacienteId, PsicologoId, Status)
- **Prontuários:** (Id, AgendamentoId, QueixaPrincipal, EvolucaoClinica, DataRegistro)