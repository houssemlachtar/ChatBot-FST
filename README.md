# ChatBot-FST
<p align="center">
A machine learning chatbot with Flask Python and Javascript in the front-end.
</p>

## Initial Setup in Windows
Make sure python is among your environment variables first.<br>
Open the whole project in VS Code <br>
Open app.py and run in a new terminal <br>
<br>
Create a virtual environment 
```
chatbot-FST\Scripts\activate
```

## Now install the dependencies 

```
python -m pip install --trusted-host pypi.python.org --trusted-host files.pythonhosted.org --trusted-host pypi.org --upgrade pip
python -m pip install --trusted-host pypi.python.org --trusted-host files.pythonhosted.org --trusted-host pypi.org pip Flask
python -m pip install --trusted-host pypi.python.org --trusted-host files.pythonhosted.org --trusted-host pypi.org pip torch
python -m pip install --trusted-host pypi.python.org --trusted-host files.pythonhosted.org --trusted-host pypi.org torchvision
python -m pip install --trusted-host pypi.python.org --trusted-host files.pythonhosted.org --trusted-host pypi.org pip nltk
```

## Running the app

```
python
>>> import ntlk
>>> nltk.download('punkt')
python train.py
python chat.py
```
At this level your chatbot should be running and appearing in the command line.

## Linking in the chatbot to the front-end

All you have to do now is to:
Press F5 to start debugging<br> 
Or<br> 
Just go to RUN in the menu bar and click start debugging<br>

## The app should be running on http://127.0.0.1:5000/

## Used Tools

<details>
  <summary>Used Libraries</summary>
  
<!--START_SECTION:activity-->
1. [Flask](https://flask.palletsprojects.com/en/2.1.x/)
2. [PyTorch](https://pytorch.org/vision/stable/index.html)
3. [Nltk](https://www.nltk.org)

</details>

## Follow me on

[Instagram](https://www.instagram.com/houssem_lachtar/), [Codepen](https://codepen.io/houssem-lachtar), [GitHub](https://github.com/houssemlachtar)
