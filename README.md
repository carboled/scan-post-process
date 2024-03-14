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
- In one block for windows
```
cd scan-post-process
python -m venv myenv
source myenv/Scripts/activate
pip install -r requirements.txt
```


# Usage
Once the script is run by:
```
python src.py /path/to/xyz/scan
```
Then a `plots/` folder must be created if the file is found.
In the `plots/` folder you may find 3 `.png` files:
- `profiles.png`
    Profile plots
- `terrain_dataarray.png`
    Surface plot using an xarray object
- `terrain_coordinates.png` 
    Surface plot using the coordinates