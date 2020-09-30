# Pykkachu

A convenience library on top of Pykka and PySM to help with common Actor Model patterns.
[Github](https://github.com/amcknight/pykkachu)

## To Do
- Expand to work with all Actor types instead of just ThreadingActors
- Create a config loader for wiring up simple Actors
- Better encapsulate Pykka and PySM so they are not imported by users of the library unless it makes sense to

## Changelog
### v0.0.3
- Made it exist by pulling it from [gab](https://github.com/amcknight/gab)
- Factored it into classes
- Pulled a Message class in from [gab](https://github.com/amcknight/gab)

## Deployment

- pipenv shell
- python3 setup.py sdist bdist_wheel
- python3 -m twine upload --repository testpypi dist/*