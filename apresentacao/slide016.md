**`path`**

<br>

Aceita o mesmo que string, com a adição de barra "`/`"

```python
@app.route('/img/<path:filepath>')
def show_img_path(filepath):
    # mostra o caminho da imagem
    return '{}'.format(os.path.join('~/www/media/', filepath))
```
