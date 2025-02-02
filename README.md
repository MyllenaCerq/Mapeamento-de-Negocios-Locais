# Mapeamento-de-Negocios-Locais

### 🚀 **Descrição do Projeto**
O **Mapeamento de Negócios Locais** é uma solução desenvolvida para automatizar a coleta de informações sobre negócios locais usando a **API do Google Places**. O objetivo principal é criar uma planilha contendo dados como nome, endereço, telefone, avaliação e site/Instagram de empresas próximas, facilitando o mapeamento de potenciais clientes.

---

## **📂 Estrutura do Projeto**
```plaintext
├── Mapeamento de Negócios/
│   ├── mapeamento.ipynb       # Código principal em Jupyter Notebook
│   ├── .env                   # Contém a chave da API do Google Places (adicionado ao .gitignore)
│   ├── negocios_locais.xlsx   # Output: Planilha gerada com os dados mapeados
│   ├── README.md              # Este arquivo
│   └── requirements.txt       # Bibliotecas necessárias para rodar o projeto
```

---

## **🛠️ Tecnologias e Ferramentas Utilizadas**
- **Python 3.x**: Linguagem de programação principal.
- **Bibliotecas**:
  - `requests`: Para fazer requisições à API do Google Places.
  - `pandas`: Para manipulação e organização de dados.
  - `openpyxl`: Para salvar os dados em uma planilha Excel.
- **Jupyter Notebook**: Ambiente interativo para rodar o código.
- **Google Places API**: Para obter os dados dos negócios locais.

---

## **🌟 Funcionalidades**
- Busca automatizada de negócios locais com base em palavras-chave.
- Coleta de informações relevantes:
  - Nome do negócio
  - Endereço
  - Telefone
  - Website ou Instagram
  - Avaliação
- Geração de uma planilha Excel com os resultados.

---

## **📋 Pré-requisitos**
1. **Conta no Google Cloud** com a API do Google Places ativada.
2. Instale as dependências do projeto:
   ```bash
   pip install -r requirements.txt
   ```
3. Configure o arquivo `.env` com sua chave da API:
   ```
   API_KEY=SUA_CHAVE_DA_API
   ```

---

## **🚀 Como Rodar o Projeto**
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/mapeamento-negocios.git
   cd mapeamento-negocios
   ```

2. Configure o ambiente virtual (opcional):
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Insira sua chave da API no arquivo `.env`.

5. Abra o **Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
   - Execute as células no arquivo `mapeamento.ipynb`.

---

## **📈 Exemplos de Uso**
### **Input:**
- Palavra-chave: "Clínicas médicas na cidade X"

### **Output:**
Planilha `negocios_locais.xlsx` com as colunas:
- Nome
- Telefone
- Site/Instagram
- Endereço
- Avaliação

---

## **🌐 API Utilizada**
Este projeto utiliza a **Google Places API**, que permite buscas baseadas em palavras-chave e localização, e fornece informações detalhadas sobre negócios.

**Requisições feitas por execução:**
- 1 requisição de busca (Text Search).
- Até 10 requisições de detalhes (Place Details).

**Limitações da API (Plano Gratuito):**
- Até 1.000 requisições gratuitas por mês.

---

## **📌 Melhorias Futuras**
- Adicionar suporte para mais dados (ex.: horários de funcionamento).
- Criar uma interface gráfica para usuários não técnicos.
- Implementar filtros mais avançados para as buscas.

---

## **🤝 Contribuição**
Sinta-se à vontade para contribuir com o projeto! Para isso:
1. Faça um fork do repositório.
2. Crie uma nova branch:
   ```bash
   git checkout -b feature/nova-funcionalidade
   ```
3. Faça o commit das suas alterações:
   ```bash
   git commit -m "Adiciona nova funcionalidade"
   ```
4. Faça o push para a branch:
   ```bash
   git push origin feature/nova-funcionalidade
   ```
5. Abra um Pull Request.

---

## **📜 Licença**
Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

---

Espero que isso deixe o repositório organizado e atraente! Se precisar de ajustes ou ajuda para colocá-lo no GitHub, só chamar! 🚀
