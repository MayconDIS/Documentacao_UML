# Nex_TI

## Product Vision
Nex_TI é uma plataforma educacional interativa ("Desktop First" / Web Version responsiva) focada em estudantes de TI (18-20 anos). Utiliza repetição espaçada (SM-2) e gamificação para maximizar a retenção de conteúdo teórico (C#, SQL, Arquitetura) visando exames como o ENADE.

## Architecture
- **Frontend**: HTML5, CSS Grid, Flexbox (WAI-ARIA).
- **Backend**: C# (.NET 10).
- **Database**: Microsoft SQL Server.
- **Security**: BCrypt for hashing, Cookies HttpOnly for JWT.
- **AI Integration**: LLM API optimized for tokens/cost.

## Actors
- **Aluno**: Estuda, ganha XP, resolve simulados.
- **Tutor**: Cria trilhas, analisa relatórios.
- **Admin**: Gerencia privilégios.
