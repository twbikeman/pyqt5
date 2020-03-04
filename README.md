```
from PyQt5.Qtwidgets import QApplication, QLabel

app = QApplication([])
label = QLabel('hello')
label.show()
app.exec_()
```
```
def hello_world(request):
	request_args = request
	if request_args and 'name' in request_args:
		name = request_args['name']
	else:
		name = 'world'
	return f'Hello {name}'
```

```
from flask import Flask, request
```
