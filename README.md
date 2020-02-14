### Designing RESTful API with Python-Flask and MongoDB

This example project demonstrate how to design RESTful API with Python-Flask and
MongoDB.

First you'll need to get the source of the project. You could do this by cloning the repository:

```bash
# Get the project code
git clone https://github.com/Moesif/moesif-flask-mongo-example.git
```

*NOTE: While working with Python, we would recommend to use virtual environment
to keep all the project's dependencies isolated from other projects.*

##### Create your local environment

```bash
conda create -n restfulapi python=3.7 anaconda # Create the environment
source activate restfulapi # Activate the environment
```

##### Install dependencies

```python
pip install -r requirements.txt
```

##### Start MongoDB Server

If you're using MacOS, you could use `brew` to start the server.

```bash
brew services start mongodb
```

#### Config the application

Change the `DBNAME` in the config file according to the database name you are using.

##### Start the application

```bash
python run-app.py
```

Once the application is started, go to [localhost](http://localhost:5000/)
on Postman and explore the APIs.

More detail on how to design RESTful API could be found [here](https://www.moesif.com/blog/technical/restful/Guide-to-Creating-RESTful-APIs-using-Python-Flask-and-MongoDB/).
