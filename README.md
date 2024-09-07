# docker-compose_withenv
This has the docker-compose which will give you the django dockerized websockets with postgres and redis

# django variables
DEBUG=False
SECRET_KEY=your-secret-key
DJANGO_SUPERUSER_USERNAME=omkar
DJANGO_SUPERUSER_PASSWORD=itachi9999
DJANGO_SUPERUSER_EMAIL=admin@example.
# Database settings
POSTGRES_DB=mydb
POSTGRES_USER=myuser
POSTGRES_PASSWORD=mypassword
POSTGRES_HOST=db
POSTGRES_PORT=5432

# Allowed hosts
ALLOWED_HOSTS=127.0.0.1,localhost,yourhostname



# Redis Configuration
REDIS_URL=redis://redis:6379