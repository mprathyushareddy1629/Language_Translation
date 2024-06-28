STEPS:

How to run?


STEP 01- Create a conda environment after opening the repository

        python -m venv venv

        venv\Scripts\activate.bat



STEP 02- install the requirements

        pip install -r requirements.txt

        if error -(RUN THIS) 
             pip install --user tbb pydub intel-openmp ffmpy websockets ujson toolz tomlkit sniffio shellingham semantic-version safetensors ruff rpds-py pyyaml python-multipart python-dotenv pydantic-core orjson networkx mkl mdurl markupsafe importlib-resources idna httptools h11 fsspec filelock dnspython certifi attrs annotated-types aiofiles uvicorn requests referencing pydantic markdown-it-py jinja2 httpcore email_validator anyio watchfiles torch starlette rich jsonschema-specifications huggingface-hub httpx typer tokenizers jsonschema gradio-client transformers fastapi-cli altair fastapi gradio


STEP 03- run application

        python app.py

after download move the model to code folder-Model


open bash 
        cd .cache/huggingface/hub/

        ls 

copy your downloaded model name and path and paste it below (it already pasted for my workspace)

mv ~/.cache/huggingface/hub/models--facebook--nllb-200-distilled-600M /c/Users/uig25512/Desktop/Language-translation/Model/ [ -- address of your Model folder]



for language codes -- https://github.com/facebookresearch/flores/blob/main/flores200/README.md