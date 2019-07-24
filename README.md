# Isogeo User oAuth2 example - Desktop Search Form

*DO NOT USE THIS CODE IN PRODUCTION*

## Usage

Run this sample:

1. Clone/download this repository
2. Open a prompt (bash, powershell...),
3. Move into this directory
4. Paste your `client_secrets.json` file. If you don't have, ask one to Isogeo!

### With your installed Python

1. Create a virtualenv (PowerShell: `py -3 -m  venv env`), then activate it

2. Install prerequisites:

    ```bash
    python -m pip install --upgrade -r requirements.txt
    ```

3. Run it:

    ```python
    # using autocompletion widgets and async/await
    python isogeo_tk_search_form_py3_async.py
    # using 'pure' ttk library
    python isogeo_tk_search_form_pure.py
    ```
