This is where cc_api will be refactored

For windows: Make sure server.py has CRLF removed

## Instructions:

Git clone, then:

```bash
$ make server.install      # Install the pip dependencies on the docker container
$ make server.start        # Run the container containing your local python server
$ make database.upgrade    # Run the migrations until your database is up to date. 
$ make database.connect    # Connect to your docker database.   
$ make test                # Run unit tests with pytest in its own container. 
```
