# 🎓 Assistente de Estudos com IA (n8n + OpenAI)

Este projeto é um workflow de automação que transforma links de vídeos do YouTube em materiais de estudo completos e estruturados no Notion.

## 🛠️ Tecnologias Usadas
- **n8n:** Orquestração do fluxo (Low-code).
- **Apify:** Web Scraping para extração de legendas/transcrição do YouTube.
- **OpenAI (GPT-4o):** Análise, resumo e geração de quiz.
- **Notion:** Banco de dados e interface de leitura.

## 🚀 Funcionalidades
1.  **Input via Formulário:** Recebe a URL do vídeo.
2.  **Scraping:** Extrai o texto completo da legenda (bypassing limitações de API).
3.  **Processamento:** Une fragmentos de texto via JavaScript.
4.  **IA Generativa:** Cria um resumo executivo, mapeia conceitos-chave e gera um quiz de 10 perguntas.
5.  **Output Estruturado:** Salva tudo em uma página formatada no Notion.

## 📦 Como Usar
1.  Baixe o arquivo `Assistente de Estudos com IA.json` deste repositório.
2.  No seu n8n, vá em "Import from File" e selecione o arquivo.
3.  Configure suas credenciais (OpenAI, Notion e Apify).
4.  Divirta-se!

---
Desenvolvido por Fabricio Navarro Meira
