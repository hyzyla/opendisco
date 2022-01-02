# opendisco

Make Slack communities trylly public

## Running
Run airbyte:
```shell
docker-compose -f docker-compose.airbyte.yaml up
```
Run app:
```shell
docker-compose up opendisco_db
```

## TODO:
- [ ] Add postgres as destination
- [ ] Add slack as source
- [ ] Add base flask app
- [ ] Add base rendering
- [ ] Deploy to digital ocean