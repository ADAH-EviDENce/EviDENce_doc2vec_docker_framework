This directory is mounted as a volume on startup up
of the docker-compose framework. It subsequently serves
as the perpetuated repository of derived data products
produced by the framework, i.e the files containing the
preprocessed corpus, as well as the model and the model
vectors for all elements of the corpus.

If an already trained model is to be used it can be placed
here. Declare the filepath to the model in the filenames
declaration file, and it will be loaded on startup and will
be accessible to the inferral-engie flask application.
