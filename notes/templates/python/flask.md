# Flask template
A basic Flask layout:

```python
from flask import Flask
from flask import render_template, request
app = Flask(__name__)


@app.route("/")
def index():
    return render_template("index.html")

```
