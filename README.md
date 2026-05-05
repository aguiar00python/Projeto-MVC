# Instale o requirements.txt

```bash
pip install -r requirements.txt
```

# iniciar o alembic
```bash
pip install -m alembic init migration
```

# gerar a migration
```bash
    python -m alembic revision --autogenerate -m "Criar tabela usuario"
```
# APLICAR A MIGRATION
```bash
    python -m alembic upgrade head
```
