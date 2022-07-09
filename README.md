# detective platform (docker-compose)

To start the detective-platform with `docker-compose` simply fill in all missing environment variables in the `.env` file (e.g. `ACCESS_TOKEN_SECRET`).

Afterwards run `docker-compose up -d` to pull & start the necessary docker containers (it might be necessary to run `docker login quay.io` and log in with your credentials first. A complete login console command incl. the necessary auth token can be generated in the `quay.io` administration).

Per default all service versions are set to `development`. The version tags can be adjusted individually in the `.env` file. After such a change all service need to be restarted in order to apply these changes to the containers.
