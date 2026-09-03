> [!IMPORTANT]
> **Repositório Central da Disciplina (DSW):**  
> Todas as atividades desta matéria foram reunidas, padronizadas e documentadas no repositório oficial:  
> 🔗 [**kellyson71/Desenvolvimento-de-Sistemas-Web**](https://github.com/kellyson71/Desenvolvimento-de-Sistemas-Web)  
> *(Acesse o link acima para visualizar o índice completo de atividades do curso de ATV-001 a ATV-007)*

---

# Atividade Introdução ao Django (Hello World)

**Disciplina:** Desenvolvimento de Sistemas Web (DSW)  
**Professor:** Irlan Arley Targino Moreira  
**Aluno:** Kellyson Medeiros  

Primeiro projeto em Django com a criação da aplicação inicial `hello_world`, configuração de rotas e retorno de resposta HTTP.

## Estrutura do Projeto
- `core/`: Configurações principais do projeto Django (`settings.py`, `urls.py`, `wsgi.py`).
- `hello_world/`: App contendo a view inicial e mapeamento de rotas.
- `manage.py`: Utilitário de linha de comando do Django.
- `requirements.txt`: Dependências do projeto (Django).

## Como Executar
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python3 manage.py runserver
```
Acesse `http://127.0.0.1:8000/` no navegador.
