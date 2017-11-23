# Setup
First you need a mongo container. Do the following steps:
1. **Get a mongo image:** docker pull mongo
2. **Run the image (store data in db):** docker run -d -p 27017:27017 -v /data:/data/db mongo
3. **Connect to the DB to test:** mongo localhost/db

