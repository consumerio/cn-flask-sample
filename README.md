=====================
Flask Sample Project
=====================

This is a sample Flask project that uses the Consumer Notebook API.

WARNING: IT DOESN'T ACTUALLY USE THE CONSUMER NOTEBOOK API AS IT SHOULD YET.  We're still working on preparing this sample for you...

Running it locally
------------------

In your terminal::

    $ git clone https://github.com/consumernotebook/cn-flask-sample.git
    $ cd cn-flask-sample
    $ mkvirtualenv cn-flask-sample
    $ pip install -r requirements.txt

To run it in debug mode locally::

    $ python runserver.py

In your browser, go to http://127.0.0.1:5000/

Note: you can also run it with Foreman, but you won't get the debugger::

    $ foreman start

Deploying it on Heroku
----------------------

Delete the runserver.py file, then follow the deployment instructions at https://github.com/zachwill/flask_heroku.  This demo is mostly based on the code from the [Flask Heroku](https://github.com/zachwill/flask_heroku) project, which is a template to get your Flask app running on Heroku as fast as possible.
