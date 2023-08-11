# Creating the postgres database
sudo docker run --name postgres12 -v /Users/keith/Documents/workspace/antifa/postgres:/var/lib/postgresql/data -e POSTGRES_PASSWORD=PASSWORD --rm -d postgres:14-alpine

