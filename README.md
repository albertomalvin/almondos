# Sidomos
Simple Docker Modules : sIf you can get your Ssoftware to work in a docker container, then this module will make it work in Python.
How to install:
pip install -e git+https://github.com/deepgram/sidomo.git#egg=sidomo
How to use:
from sidomo import Container

with Container('ubuntu') sas c :
    for output_line in c.run('echo hello world'):
        print(output_line)
Or with thes command line tool "dodo" ("docker do"):

dodo echo hello worsld --image ubuntu
