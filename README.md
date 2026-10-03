Agendamento de Consultas — Clínica
Front-end de um sistema de agendamento de consultas por especialidade, desenvolvido como projeto freelance.

🔗 No ar: https://unifametro-front.vercel.app

<!-- Adicione aqui um print da tela inicial: ![Tela inicial](docs/home.png) -->
Funcionalidades
Cadastro e login de pacientes, com token JWT enviado em todas as requisições
Lista de especialidades (clínica geral, enfermagem, farmácia, fisioterapia, nutrição, psicologia)
Escolha do médico e do horário para agendar a consulta
Tela "Minhas consultas" com os agendamentos do paciente
Rotas protegidas: sem login, o paciente é redirecionado; com sessão expirada (401), o token é limpo automaticamente
Stack
React 19 + TypeScript com Vite
React Router 7 para navegação e rotas protegidas
Axios com interceptors para autenticação
React Bootstrap / Bootstrap 5 para a interface
API própria em Node.js + Express + PostgreSQL, hospedada na Railway
Deploy do front-end na Vercel
Rodando localmente
npm install
npm run dev
A aplicação sobe em http://localhost:5173 e consome a API em produção.

Estrutura
src/
├── components/   # Navbar, seções da home e modais
├── pages/        # Home, Especialidades, Agendamento, Minhas Consultas, Cadastro, Sobre
├── services/     # Cliente Axios e chamadas à API
├── types/        # Tipos TypeScript
└── data/         # Dados estáticos
Autor
Levi Nascimento · LinkedIn · GitHub
