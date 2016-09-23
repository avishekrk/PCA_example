#PCA Example

## Set up the environemnt on Saguaro

SSH into Saguaro
```
ssh -L 44444:localhost:44444 <asurite>@saguaro.fulton.asu.edu
```

### Load Python
```
module load python/2.7.12
```

### Clone the Repo
```
git clone https://github.com/avishek-r-kumar/PCA_example.git
```

### Enter the directory and install virtual env
```
cd PCA_example
pip install virtualenv --user
export PATH=~/.local/bin:$PATH
virtualenv venv --no-site-packages
source ./venv/bin/activate
pip install -r requirements.txt
```

### Run the Jupyter Notebook
```
jupyter notebook --no-browser --port 44444
```

