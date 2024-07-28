# Flask_blueprint_elastic
for example .env file:
SECRET_KEY = os.environ.get('SECRET_KEY') or 'qwerty'

SQLALCHEMY_DATABASE_URI = 'mysql+mysqlconnector://cubinez85:123@localhost/testdb'

ELASTICSEARCH_URL=https://localhost:9200
ELASTICSEARCH_CA_CERTS=./http_ca.crt
ELASTICSEARCH_USERNAME=elastic
ELASTICSEARCH_PASSWORD=********
