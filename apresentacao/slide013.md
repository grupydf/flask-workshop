# Regras Variáveis
## string

É o conversor padrão e aceita texto sem barra `/`

```python
@app.route('/user/<username>')
def show_user_profile(username):
    # mostra o nome de usuário
    return 'O usuário é {}'.format(username)
```
