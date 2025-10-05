how it works:
[optional] generate an env in the folder to contain python modules

generate env using

```bash
  python -m venv env
```

start env using

```bash
    source env/bin/activate
```

then install using

```bash
    pip install -r ./requirements.txt
```

add a urls.csv to with name, url these columns, see the example_urls.csv to check format.

then run the jupyter notebook cells one by one to generate qr codes that are saved with the name of the user in the name sake folder.
