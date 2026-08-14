# 🎓 Validação de Certificados — Mobilizadores Gemini

Sistema web público para consulta e verificação de autenticidade dos certificados emitidos na formação **Mobilizadores Gemini**, coordenada por **Savio Ferraz**.

---

## 🚀 Como Funciona

1. O participante digita o **Código de Validação** único recebido por e-mail no ato do encerramento da formação (ex: `GEM-XXXXXX`).
2. A aplicação faz uma requisição para uma API Serverless construída em **Google Apps Script**.
3. A API consulta a base de dados oficial e retorna instantaneamente:
   - **Nome Completo do Participante**
   - **Nome da Formação/Evento**
   - **Data e Horário da Emissão**
   - **Status de Autenticidade**

---

## 🛠️ Tecnologias Utilizadas

- **Frontend:** HTML5, CSS3, JavaScript (Fetch API)
- **Hospedagem Frontend:** GitHub Pages
- **Backend / API:** Google Apps Script (Web App Endpoint)
- **Banco de Dados:** Google Sheets

---

## 🔒 Segurança e Autenticidade

Cada certificado emitido possui um token identificador gerado dinamicamente no momento do processamento dos dados. A validação consulta diretamente a fonte original, garantindo a integridade e prevenindo adulterações.

---

Atenciosamente,  
**Equipe Savio Ferraz / Mobilizadores Gemini**
