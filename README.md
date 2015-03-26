# MicroBlog
Web Applications in Python using the Flask Micro Framework, starting with Hello World

![](http://blog.miguelgrinberg.com/static/flask-intro-cover-tiny.png)
## Setup
```python
from app import app

@app.route('/')
@app.route('/index')
def index():
    return "Hello, World!"
```


[Click here to follow the rest of the tutorial](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)