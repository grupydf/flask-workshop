### Criando a blueprint

```python
# views.py
# ...

profile = Blueprint('profile', __name__,
                    template_folder='templates',
                    static_folder='static')
```

<br>

### Registrando a blueprint

```
# __init__.py

from flask import Flask
from .views.profile import profile

app = Flask(__name__)
app.register_blueprint(profile)
```
