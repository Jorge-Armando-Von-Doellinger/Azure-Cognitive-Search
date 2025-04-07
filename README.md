# Azure Cognitive Search
# 🔎 Azure Cognitive Search – Projeto de Pesquisa Inteligente com IA

Este projeto tem como objetivo demonstrar a configuração e uso do **Azure Cognitive Search**, uma solução poderosa para implementar **pesquisas inteligentes com enriquecimento cognitivo** em documentos armazenados na nuvem.

---

## 📁 Etapas de Configuração da Pesquisa Cognitiva

### 1. Criar o Serviço de Pesquisa
- Acesse o [Portal do Azure](https://portal.azure.com)
- Procure por **"Azure Cognitive Search"** e clique em **"Criar"**
- Escolha a **camada gratuita (F0)**, se disponível, para testes
- Defina: nome do recurso, grupo de recursos e região

---

### 2. Criar a Fonte de Dados
- Pode ser um **Azure Blob Storage**, **Cosmos DB**, **SQL Database**, etc.
- Os documentos podem estar em formatos como PDF, DOCX, JSON ou HTML
- Certifique-se de que os arquivos estejam organizados e com permissões corretas

---

### 3. Criar o Índice
- Crie os **campos** a serem pesquisados: `id`, `titulo`, `conteudo`, `autor`, `data`, etc.
- Configure os campos como **pesquisáveis**, **filtráveis**, e **retornáveis**, conforme necessário

---

### 4. Criar um Skillset (Habilitador Cognitivo)
- Adicione **habilidades (skills)** como:
  - Extração de texto e frases-chave
  - Tradução automática
  - Detecção de idioma
  - Análise de sentimentos
  - OCR (para imagens)
- Essa etapa é opcional, mas enriquece muito o conteúdo indexado

---

### 5. Criar um Indexador
- Vincule a **fonte de dados** ao **índice** criado
- Execute o indexador para que os dados sejam processados e enriquecidos
- Pode ser executado manualmente ou agendado

---

### 6. Consultar e Integrar
- Use o **explorador de busca** dentro do Azure para testar pesquisas
- Ou integre com apps e sites por meio de APIs REST ou SDKs (Python, C#, JS)

---

## 💡 Possibilidades com a Pesquisa Cognitiva

Ferramentas que podem se beneficiar:

- 🏛 **Jurídico**: busca em contratos e legislações
- 🧾 **Financeiro**: análise de relatórios e transações
- 🧑‍🎓 **Educação**: organização e consulta de material didático
- 🏥 **Saúde**: análise de prontuários e exames
- 📚 **Portais de conteúdo**: sistema de busca por artigos e documentos
- 💬 **Atendimento ao cliente**: base de conhecimento e respostas rápidas

---

## 🧠 Insights e Aprendizados

- A Pesquisa Cognitiva combina **busca semântica** com **IA aplicada a documentos**
- Mesmo documentos não estruturados podem ser processados de forma inteligente
- Permite extrair **entendimento real do conteúdo**, indo além de buscas por palavra-chave
- É escalável, personalizável e compatível com múltiplas fontes e formatos

---

## 🙌 Agradecimentos

Agradeço à **DIO** e à **Avanade** pela oportunidade de explorar o módulo de **Inteligência de Documentos e Pesquisa Cognitiva com IA do Azure**, que proporcionou aprendizados valiosos sobre como IA pode ser aplicada de forma prática na busca e organização de conhecimento.

---
