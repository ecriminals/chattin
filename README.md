# Chatting
### Python-based package that answers simplistic questions and can be taught by human input.

# Examples
### Ask Question
```py
from chattin import client

cli = client(debug=False) # debug=True
def ask(q: str):
  return cli.ask(q)
  
ask("hi!")
```
