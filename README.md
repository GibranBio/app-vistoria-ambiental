# app-vistoria-ambiental
tabela para preenchimento da vistoria

# app-vistoria-ambiental

App em Streamlit para preencher checklist de condicionantes/medidas de mitigação em vistorias de obra e gerar um arquivo Excel padronizado (para posterior geração de relatório em PDF).

## O que o app faz
- Permite preencher **Peso**, **Status** e **Recomendação** por condicionante
- Gera e disponibiliza para download um **.xlsx** padronizado (template)
- (Opcional/futuro) Geração automática do relatório em PDF

## Estrutura do repositório
- `app.py` — aplicação Streamlit
- `requirements.txt` — dependências Python
- `assets/Checklist_template.xlsx` — template Excel usado como base

## Rodar localmente
```bash
pip install -r requirements.txt
streamlit run app.py
</>Markdown
