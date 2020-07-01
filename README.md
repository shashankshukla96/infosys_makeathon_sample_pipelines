# infosys_makeathon_sample_pipelines
This repository contains 5 sample pipelines, used as a reference for all the participating teams.


*Pipeline 1: This pipeline will read a file, remove some fields form the it and wwrite this data into another file, this pipeline has a pipeline finisher, which gets trigerred when no-more-data event occurs.

*Pipeline 2: This pipeline reads data from the output file of first Pipeline.

*Pipeline 3: this Pipeline reads data from a REST URL, and saves that JSON data to MongoDB.

*Pipiline 4: This pipeline reads data from a database with JDBC, and writes that to a File, also when the no-mpre-data event is passed, then It will send a mail to the given mail address (To configure mailer, visit Streamsets docs)

*Pipelin 5: This Pipeline shows how can we configure different entites like Elastic seach, Geo IO, field Converter.
