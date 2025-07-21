# 🧠 Analisador TAE - Sistema Web para Técnicas de Análise Estruturada

Este é um sistema completo para aplicação prática de **Técnicas de Análise Estruturada (TAE)** com apoio de inteligência artificial (OpenAI/GPT).  
Permite login, execução de análises, geração de relatórios DOCX/PDF e histórico por usuário.

## 🔗 Acesse o sistema

📌 **Login:** [login_tae_render.html](./login_tae_render.html)  
🔒 Requer autenticação com usuário/senha válidos cadastrados no backend.

## ⚙️ Tecnologias

- Frontend: HTML + JS (puro)
- Backend: FastAPI + OpenAI API
- Banco: SQLite
- Relatórios: DOCX (python-docx) e PDF (fpdf)
- Auth: JWT com login seguro
- Hospedagem:
  - Backend na [Render.com](https://render.com)
  - Frontend via GitHub Pages

## 🚀 Como usar

1. Faça login com usuário e senha válidos
2. Escolha uma técnica:
   - ACH
   - PMESIIAT
   - Matriz SWOT
   - Linha do Tempo
   - Análise de Vínculos
   - Advogado do Diabo
3. Descreva o problema a ser analisado
4. Clique em **Executar**
5. Visualize o resultado e baixe o relatório
6. Veja seu histórico na aba “Ver Histórico”

## 🛡️ Segurança

- Toda a comunicação com a API usa **token JWT**
- O backend só responde a usuários autenticados
- Relatórios são individuais e exclusivos por login

## 🗃️ Repositórios recomendados

- `backend/`: código FastAPI e geração de relatórios
- `frontend/`: este repositório com os HTMLs interativos

## ✍️ Contato

Desenvolvido com apoio de IA. Para dúvidas ou melhorias, entre em contato com o administrador do projeto.