## venv

### перейти в нужную папку
    cd ...\folder

### создать папку виртуальной среды .venv
    python -m venv .venv

### активировать venv
    .venv\Scripts\activate

### просмотреть пакеты
    pip list

### установить пакеты
    pip install -r requirements.txt

### выгрузить пакеты
    pip freeze > file.txt

### для отключения venv, либо закрыть консоль
    (.venv) ...\folder> deactivate

### путь для добавления интерпретатора
    .venv/
    └── Scripts/
        └── python.exe
