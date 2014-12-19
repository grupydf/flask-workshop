# Regras Variáveis
## float

Aceita números de ponto flutuante

```python
@app.route("/map/<float:latitude>/<float:longitude>")
def show_coords(latitude, longitude):
    # mostra as coordenadas informadas
    return 'Latitude: {0} Longitude: {1}'.format(latitude, longitude)
```

<small>**Atenção:** <!-- .element: style="color: red" --> `'/map/10/10' != '/map/10.0/10.0'`</small> <!-- .element: class="fragment" data-fragment-index="1" -->
