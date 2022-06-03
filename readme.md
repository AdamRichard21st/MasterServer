# Important

**Note**: You must to have [docker](https://docs.docker.com/desktop/linux/install/ubuntu/) & [docker-compose](https://docs.docker.com/compose/install/) installed.

## Commands

```bash
# Start container
docker-compose up -d

# Start masterserver proccess (press ctrl+A & ctrl+D to leave the proccess)
docker-compose exec masterserver bash start

# Connect to a executing masterserver proccess (press ctrl+c to stop the proccess)
docker-compose exec masterserver screen -x ms
```