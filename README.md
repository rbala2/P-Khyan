### <u>Project P-Khayn</u>

<li> Accelerator</li>
<li>Helpers</li>

### <u> Accelerator</u>

Accelerator project is a python - django based CMS application. which is intended to deliver Video and text based
lessons.
It also hosts Student evaluation application.

### <u> Helpers</u>

Helper lib is python package that includes the commonly used code across all components in Project Khyan. It can be
distributed by PYPI.

### Settng local env to run Accelerator and contribute

1. Install python 3.9 stable release from python.org.
2. clone the project P-Khyan.
   `git clone https://github.com/rbala2/P-Khyan.git`
3. setup a virtual env, runt he below command in terminal.
   `python -m venev venv-django4`
   use any preferred IDE (Pycharm, IntelliJ, vscode).set the project interpreter to ven-django4.
4. install the dependencies.
   `pip install -r Components/accelerator_main/requirements.txt`
5. Launch the Application.
   `cd ~/Components/accelerator_main/accelerator`
   `python manage.py runserver`


