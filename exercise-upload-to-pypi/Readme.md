In this part of the lesson, you'll practice uploading a package to PyPi. 

You'll need to create a `setup.cfg` file, a `README.md` file (replace this file), and a `LICENSE.txt` file. You'll also need to make two accounts: one for the PyPi test repository and one for the PyPi repository.

Don't forget to keep your passwords; you'll need to type them into the command line.

Once you have all the files set up correctly, you can use the following commands on the command line (note that you need to make the name of the package unique, so change the name of the package from distributions to something else. That means changing the information in `setup.py` and the folder name):
```bash
cd 5_exercise_upload_to_pypi
python setup.py sdist
pip install twine
```
```bash
# commands to upload to the PyPi test repository
twine upload --repository-url https://test.pypi.org/legacy/ dist/*
pip install --index-url https://test.pypi.org/simple/ distributions
```
```bash
# command to upload to the PyPi repository
twine upload dist/*
pip install distributions
```
If you get stuck, rewatch the previous video showing how to upload a package to PyPi.