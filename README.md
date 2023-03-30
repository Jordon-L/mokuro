# mokuro

Read Japanese manga with selectable text inside a browser.

This is a modified verison of Mokuro for Mokuro Desktop.

Please go [here](https://github.com/kha-white/mokuro) for the original.

# Compile to EXE
1. create a virtual python environment
2. get Auto PY to EXE
3. install all packges via pip
4. download manga-ocr model from hugging face and put in folder called models
4. run Auto PY to EXE and under settings import config file.
5. modify your script location and additional files to match your directory.
6. Click Convert .PY to .EXE 

```commandline
pip install auto-py-to-exe
pip install -r requirements.txt
cd comic_text_detector
pip install -r requirements.txt
auto-py-to-exe
```
