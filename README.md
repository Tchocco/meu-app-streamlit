# Análise Estatística da Lotofácil

Este projeto realiza uma análise completa dos concursos da Lotofácil, com base em dados históricos, e gera estatísticas e sugestões de jogo.

## Funcionalidades
- Frequência geral das dezenas
- Repetições entre concursos pares e ímpares
- Dezenas novas por concurso
- Análise de linhas, colunas, pares, ímpares e soma
- Sugestão de jogo com base estatística

## Como executar localmente
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Como publicar online (Streamlit Cloud)
1. Crie um repositório no GitHub com esse código.
2. Acesse [https://streamlit.io/cloud](https://streamlit.io/cloud).
3. Clique em "Deploy an app".
4. Conecte com seu GitHub e selecione o repositório.
5. No campo de arquivo, insira: `app.py`.

Seu app será publicado com um link público.

## Estrutura
- `main.py`: execução via terminal
- `app.py`: execução via web com Streamlit
- `utils/`: módulos auxiliares
- `data/lotofacil.csv`: dados dos concursos

---
Feito para fins estatísticos e educacionais.
