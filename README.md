A basic frame to run your notebook with h2o in a virtual env. Assume python3.6 is installed

# Set the virtual env
 `python -m venv my_virtualenv`  
 `source my_virtualenv/bin/activate`  
 `pip install --upgrade pip`  
 `pip install -r requirements.txt`  
 `jupyter notebook --port=8880 --no-browser`  

# Work on a distant machine, locally run
`ssh -N -f -L localhost:8888:localhost:8888 you@distant`  

