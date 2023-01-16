## this is very good flask template
# contains:
    # sqlalchemy
    # CORS


    # update DB create 
    with app.app_context():
        db.create_all()
        app.run(debug=True)

# run:
    create a virtual enviroment
    pip install -r .\requirements.txt
    flask run