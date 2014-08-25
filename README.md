githubpm
========

process mining project for github

configure PyGithub:

clone develop_v2 branch!!!

git clone git@github.com:jacquev6/PyGithub --branch develop_v2
cd PyGithub
pip install -r requirements.txt
python setup.py install
cd ..
python -c "import PyGithub"

>>> import PyGithub

>>> g = PyGithub.BlockingBuilder().Build()

>>> u = g.get_user("jacquev6")
>>> print u.name
Vincent Jacques

>>> r = u.get_repo("PyGithub")
>>> print r.stargazers_count
437

In Mac:
Copying PyGithub-2.0.0_alpha.4-py2.7.egg to /usr/local/lib/python2.7/site-packages
add 
/usr/local/lib/python2.7/site-packages

to 

Apatana >> Preferences >> PyDev>> Interpreters >> Python Interpreter >> New Folder