# Web Scraping em Python

Projetos de coleta automatizada de dados (**web scraping**) em Python, incluindo extração de informações de livros e de dados do Instagram, com exportação para planilha/CSV.

## Tecnologias
- Python 3
- Bibliotecas de scraping (ex.: requests / BeautifulSoup / Selenium)
- Pandas (exportação para Excel/CSV)

## Estrutura
| Arquivo | Descrição |
|---------|-----------|
| `books.py` | Scraping de dados de livros |
| `roboinstagram.py` | Coleta de dados/reels do Instagram |
| `dados.xlsx` / `reels_data.csv` | Resultados exportados |

## Como executar
```bash
pip install requests beautifulsoup4 pandas openpyxl
python books.py
```
> Faça scraping de forma responsável, respeitando os Termos de Uso de cada site.
