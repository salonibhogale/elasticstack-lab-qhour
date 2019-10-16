# Parliamentary Questions with Elastic Stack

### Prerequisites

You need to install Docker & Docker Compose on your system. You can install Docker by going to this url
https://docs.docker.com/install/

### Installing

Clone this repo to any path at your local machine

Run docker-compose:

cd elasticstack-lab-qhour <br/> 
docker-compose up

After build process finishes you will be able to enter Kibana and see some sample parliamentary questions data

### Enter Kibana

Now open your browser and navigate to http://localhost:5601
Configure the index (search: sample-small-), use without the Time Filter

docker-compose configurations adapted from: https://github.com/moryachok/elasticstack-lab
