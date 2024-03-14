# Clone
via ssh:
```
git clone git@github.com:carboled/scan-post-process.git
```
or via https:
```
git clone https://github.com/carboled/scan-post-process.git
```

# Make environment

- move to folder
```
cd scan-post-process
```
- make a new environment
```
python -m venv myenv
```
- UNIX: activate environmemt
```
source myenv/bin/activate
```

- WINDOWS: activate environmemt
```
source myenv/Scripts/activate
```

- Install requirements
```
pip install -r requirements.txt
```
- In one block for windows and https
```
git clone https://github.com/carboled/scan-post-process.git
cd scan-post-process
python -m venv myenv
source myenv/Scripts/activate
pip install -r requirements.txt
```


# Usage

```
python src.py /path/to/xyz/scan
```