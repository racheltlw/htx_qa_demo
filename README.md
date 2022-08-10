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

If virtualenv is not found, then install it 
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
### 3. 