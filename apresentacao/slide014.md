**`int`**

<br>

Aceita números inteiros

```python
@app.route('/post/<int:post_id>')
def show_post(post_id):
    # mostra o post relativo ao id informado
    return 'Post {}'.format(post_id)
```
