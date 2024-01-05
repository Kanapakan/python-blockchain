**Activate the virtual environment**
```
source blockchain-env\bin\activate
```

**Install all packages**
```
pip3 install -r requirements.txt
```

**Upgrade pytest**
```
pip3 install --upgrade pytest
```

**Run the tests**
Make sure to activate the virtual environment.
```
python3 -m pytest backend/tests
```