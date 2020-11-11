# Random numerical app.

# Linux
```bash
export FLASK_APP=rando.py # Run this command first on your terminal.
python3 -m flask run  # And secondly run this command on your terminal.
```

# For windows users 
```bash
set FLASK_APP=rando.py # Run this command first on terminal.
python -m flask run # And second command. 
```
# Images for the uniform and random button generators. 
```bash
docker build . -t rando-image
docker run --name rando-container -d -p 5000:5000 rando-image
```