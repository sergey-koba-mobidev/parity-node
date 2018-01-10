# First run
- first sync clock between host and containers `docker run --rm --privileged alpine hwclock -s`
- `docker-compose run eth signer new-token`
- `docker-compose up -d`
- go to (http://localhost:8180)[http://localhost:8180], wait for project sync.
- go to Settings and enable `Contracts` section.