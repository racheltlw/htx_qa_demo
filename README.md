## QA quick start 
Navigate to htx_qa_demo on your computer
```
cd <yourpath>/htx_qa_demo
```
### 1. Check if you have virtual environment, if not install it

For linux/mac
```
which virtualenv 
```

For windows
```
where virtualenv 
```

If virtualenv is not found, then install it (you can also use pip3)
```
pip install virtualenv
```

### 2. Create a virtual environment and install packages

Create virtual environment
```
virtualenv htx_demo
```
Activate virtual environment 
For linux/mac
```
source htx_demo/bin/activate
```
For windows
```
htx_demo\Scripts\activate
```
Install packages
```
pip install -r requirements.txt
```
### 3. Download Torch based on your machine requirements 
https://pytorch.org/get-started/locally/

I used this command: 
```
pip3 install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu113
```

### 4. Download Haystack 
```
pip install git+https://github.com/deepset-ai/haystack.git
```

### 5. Open Jupyter notebook to run QA demo
Add virtual environment to Jupyter notebook 
```
python -m ipykernel install --user --name=htx_demo
```
Launch Jupyter notebook (you may need to pip install jupyter if you do not have it)
```
jupyter notebook
```
