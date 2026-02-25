# barberConnectMobile
Projeto da disciplina de multiplataforma para desenvolvimento do app de agendamento de serviços de barbearia. 

BarberConnectMobile
Escopo do app

Objetivo: permitir que o cliente encontre disponibilidade e agende serviços com barbeiros, receba lembretes e acompanhe seus agendamentos.

Funcionalidades (MVP do semestre)
Autenticação do cliente
Criar conta / login / recuperar senha
Perfil do cliente
Dados básicos (nome, telefone) e preferências (ex: barbeiro favorito)
Catálogo de serviços
Lista de serviços (corte, barba, combos), duração e preço
Agendamento
Escolher barbearia (se tiver mais de uma), serviço, barbeiro e horário
Confirmar agendamento e gerar “comprovante” (detalhe do agendamento)
Meus agendamentos
Lista (próximos e histórico)
Cancelar (com regra de antecedência)
Notificações/Lembretes
Push/local (ex: 24h antes e 1h antes) e/ou e-mail (opcional)
Calendário/Agenda
Visual por dia/semana com os horários disponíveis

Tecnologias (simples e diretas)
Front-end Mobile: React Native (Expo)
Back-end (API): Node.js + Express (REST)
Banco relacional: PostgreSQL
Autenticação: JWT (token)
Docs da API: Swagger/OpenAPI
Deploy (simples): Render/Railway/Fly.io (API + Postgres) ou AWS (se preferir)
Notificações: Expo Notifications (push) + agendamento local de lembretes
