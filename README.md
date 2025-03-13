# OpenAI API Example

This is a simple example demonstrating how to use the OpenAI API to query a model.

> [!NOTE]
> **These instructions are for unix-based systems (i.e. MacOS, Linux). Before you proceed, make sure that you have installed `python` and `pip`. If you have not, follow [these](https://packaging.python.org/en/latest/tutorials/installing-packages/) instructions to do so.**

#### 1. Create a `.env` file:
```
cp .env.example .env
```

#### 2. Add your API key to the `.env` file.

#### 3. Create Python virtual environment:
```
python3 -m venv .venv
```

#### 4. Activate Python virtual environment:
```
source .venv/bin/activate
```

#### 5. Install dependencies:
```
pip install -r requirements.txt
```

#### 6. Run the script:
```
python3 model.py
```
Expected output:
```
Connecting to model...

To exit just type 'exit' and press enter or press Ctrl+C.

Query model:
```

#### 7. Query away! To exit just type `exit` and press enter or press `Ctrl`+`C`.