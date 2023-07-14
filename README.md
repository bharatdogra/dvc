```
conda create -p venv python=3.8 -y
```

```
git init
```

```
touch .gitignore
```

```
touch README.md
```

```
pip install -r requirements.txt
```

```
dvc repro
```

```
dvc dag
## direct acyclic graph
```

'''
dvc add <file name>
'''

'''
git add <file names> && git commit -m 'files added successfully"
'''

'''
dvc remote add myremote <any remote location>
'''

'''
dvc push
'''
