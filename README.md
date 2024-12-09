# code_challenge


### Installation
Using a virtual environment (Recommended):
```
python -m venv venv
source venv/bin/activate  # On macOS/Linux

pip install -r requirements.txt
Handling any missing libraries: If the installation encounters issues, you can use pip install --upgrade --force-reinstall -r requirements.txt to force reinstall or update any problematic packages.
```
Re-install libraries(Optional)
```
pip freeze | xargs pip uninstall -y
pip install -r requirements.txt
pip install jupyterlab ipykernel
```

