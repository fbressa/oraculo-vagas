# Oráculo de Vagas

O **Oráculo de Vagas** é uma aplicação web que ajuda estudantes a encontrar oportunidades de estágio de forma rápida, filtrando por cidade, área e modalidade (remoto, híbrido ou presencial). As vagas são coletadas automaticamente de sites populares usando web scraping.

---

## Funcionalidades (MVP)

- Interface simples para inserir preferências de busca
- Coleta automática de vagas via scraping
- Exibição das 10 vagas mais recentes
- Log das buscas feitas
- Armazenamento das vagas encontradas

---

## Tecnologias

- Python 3
- Flask
- SQLite
- Requests + BeautifulSoup
- HTML + CSS (básico)

---

## 📦 Como rodar localmente

```bash
git clone https://github.com/seu-usuario/oraculo-vagas.git
cd oraculo-vagas
python3 -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate no Windows
pip install -r requirements.txt
python run.py
