django.nV
=========

django.nV is a vulnerable Django application.

Set Up
------

First, make sure Python 3.4+ is installed on your machine. On OSX, this can be installed with Homebrew (eg. `brew install python3`). If you receive an error about conflicting PYTHONPATH, try updating the variable to reflect your python version.
```
export PYTHONPATH="/usr/local/lib/python3.4/site-packages
```

To set up the repository, use `virtualenv --python=python3 venv`, which will create a virtualenv using the python3 binary. To enter this environment, run `source venv/bin/activate`. You should see your $PS1 update to include `(venv)`, reminding you that you are in the virtual environment. You can also leave the environment by simply typing `deactivate`.

To install the dependencies, simply run `pip install -r requirements.txt`.

To run the app in its application folder, use"python manage.py runserver" or the included `runapp.sh` shell script. You should then be able to access the web interface at `http://localhost:8000/taskManager`

