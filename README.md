# mokuro

Read Japanese manga with selectable text inside a browser.

This is a modified verison of Mokuro for Mokuro Desktop.

Please go [here](https://github.com/kha-white/mokuro) for the original.

# Compile to EXE
1. Create a virtual python environment
2. Get [Auto PY to EXE](https://pypi.org/project/auto-py-to-exe/)
3. Install all packages via pip
4. Download [manga-ocr model](https://huggingface.co/kha-white/manga-ocr-base) from hugging face and put in folder called models.
5. Run Auto PY to EXE and under settings import config file.
6. Modify script location
7. Under Additional Files, modify to match your paths.
8. Under Advance, modify --paths
9. Click Convert .PY to .EXE

```commandline
pip install auto-py-to-exe
pip install -r requirements.txt
cd comic_text_detector
pip install -r requirements.txt
auto-py-to-exe
```

Directory structure for models should look like this

```commandline
models/
├─manga-ocr-base
```
