# detective platform (docker-compose)

To start the detective-platform with `docker-compose` simply copy the `.secrets.example` file, rename it to `.secrets` and fill in the needed variables.

Afterwards run `docker-compose up -d` to pull & start the necessary docker containers (it might be necessary to run `docker login quay.io` and log in with your credentials first. A complete login console command incl. the necessary auth token can be generated in the `quay.io` administration).
