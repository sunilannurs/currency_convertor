# currency_convertor
currency_converting

step 1: "create the virtual environment and activate"

    python3 -m venv virt_env && source virt_env/bin/activate

step 2:"Run the requirement.txt"

    python3 -m pip install -r requirements.txt

step 3: "migrate the file"

    python3 manage.py migrate


step 4: "Run the server"

    python3 manage.py runserver


step 5:"Url in the browser"

       localhost:8000 or 127.0.0.1:8000