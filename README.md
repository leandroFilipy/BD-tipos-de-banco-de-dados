# 📊 Banco de Dados — Modelos e Características

**Autores:** Nathália, Emanuelle e Leandro  
📚 **Disciplina:** Banco de Dados  
📅 **Ano:** 2024  

---

## 🌳 Banco de Dados Hierárquico

- Organizado como uma **árvore**: cada registro tem um **pai** e pode ter **vários filhos**.
- Comum em:  
  - Organogramas de empresas 🏢  
  - Sistemas operacionais para diretórios de arquivos 💻  

### ✅ Vantagens
- Eficiência na recuperação de dados 🚀  
- Integridade e consistência 🔐  
- Simplicidade na implementação 🧩  
- Bom desempenho com grandes volumes 📦  

### ❌ Desvantagens
- Estrutura rígida 🧱  
- Escalabilidade difícil 📉  
- Redundância de dados 📄📄  
- Consultas limitadas 🔍  
- Dificuldade na manutenção 🛠️  
- Falta de padronização ❗  

### 📌 Exemplo
- **IMS Database** (IBM)  
- Acesso com a linguagem **DL/I (Data Language One)**

---

## 🌐 Banco de Dados em Rede

- Estrutura em **grafo**, com **relacionamentos muitos-para-muitos** ↔️  
- **Nódulos (nós):** representam registros  
- **Arestas:** representam conexões  

### 📍 Onde é utilizado?
- Sistemas legados, engenharia, redes sociais 🌐

### 💬 Linguagens utilizadas:
- IDMS (DML), TurboImage (DML)

### ✅ Vantagens
- Representa relacionamentos complexos 🧠  
- Suporte a hierarquias e muitos-para-muitos 🔄  
- Escalável 📈  

### ❌ Desvantagens
- Complexidade na manutenção 🧰  
- Poucas ferramentas disponíveis ⚙️  
- Falta de padronização 🔧  

### 📌 Exemplos
- **IDS**  
- **RelaX**

---

## 📑 Banco de Dados Relacional

- Dados organizados em **tabelas** (linhas e colunas) 📊  
- Usa **chaves primárias e estrangeiras** para relacionar os dados  

### 📍 Aplicações:
- E-commerce, gestão de clientes, inventário, ERP 🛒💼

### ✅ Vantagens
- Integridade referencial 🔐  
- Consultas complexas com SQL 🧠  
- Suporte a transações 💳  

### ❌ Desvantagens
- Estrutura rígida 📏  
- Escalabilidade limitada 🧱  

### 💻 Exemplos de SGBDs:
- **MySQL**, **Oracle**, **PostgreSQL**

### 🏢 Empresas que usam:
- Vivo, Itaú, Microsoft, Yahoo, Dell

---

## 🎮 Banco de Dados Orientado a Objetos

- Dados armazenados como **objetos** (com atributos e métodos)  
- Integração natural com linguagens OO como Java, C++, Python 🧬

### ✅ Vantagens
- Reutilização de código ♻️  
- Modelagem próxima do mundo real 🌍  
- Navegação expressiva nos dados 📡  

### ❌ Desvantagens
- Baixo desempenho em aplicações comerciais 🐢  
- Pouca compatibilidade com SQL tradicional 🧩  
- Complexidade no aprendizado 📚  

### 📌 Exemplo:
- **db4o (Database For Objects)**

### 🏢 Usado por:
- **Nasa** 🚀  
- **Motorola** 📱  

---

## 💾 Banco de Dados Não Relacional (NoSQL)

- Dados **não estruturados** ou **semiestruturados** (JSON, XML, etc.)  
- Não se limita a tabelas — mais flexível para escalar e modelar dados modernos 📈  

### ✅ Vantagens
- Flexibilidade 🌀  
- Alta escalabilidade 🌍  
- Ideal para grandes volumes de dados multimídia (vídeo, imagem, texto) 📷🎥📝  

### ❌ Desvantagens
- Poucas ferramentas compatíveis 🧰  
- Suporte limitado 🔍  

### 💬 Linguagens:
- MQL, HTTP, CQL  

### 📌 Exemplos:
- **CouchDB**, **Elasticsearch**

### 🏢 Empresas que usam:
- **Google**, **Amazon**, **Netflix**

---

> 🎓 Este documento apresenta uma visão geral dos principais **tipos de Banco de Dados**, suas estruturas, vantagens e limitações — ideal para estudo, consulta técnica ou uso acadêmico.
