# postgrest

# postgrest.conf

# The standard connection URI format, documented at
# https://www.postgresql.org/docs/current/static/libpq-connect.html#AEN45347
db-uri = "host=host user=user port=5432 dbname=dbname password=pass"

# The name of which database schema to expose to REST clients
db-schema = "api"

# The database role to use when no client authentication is provided.

db-anon-role = "anon"
