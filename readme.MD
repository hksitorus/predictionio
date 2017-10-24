PredictionIO + Universal Recommender as a Docker container

Include only spark.
Connect to remote mysql and elasticsearch

Set environment when running docker (used by files/pio-env.sh):
MYSQL_JDBC
MYSQL_USER
MYSQL_PASS
ELASTICSEARCH_HOST
ELASTICSEARCH_PORT

PredictionIO build with:
./make-distribution.sh -Dscala.version=2.11.11 -Dspark.version=2.1.1 -Delasticsearch.version=5.5.2