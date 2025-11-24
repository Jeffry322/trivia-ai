## Running application in debug mode
1. **Clone the repo and cd into it**
```
git clone https://github.com/Jeffry322/trivia-ai
cd trivia-ai
```
2. **Run docker-compose file**
  - To run full stack (API, Frontend, Gateway, Infrastructure) do:
```
docker-compose --profile app up -d --build
```

  - To tear it down:

```
docker-compose --profile app down
```
  - To run only infrastructure do:
```
docker-compose up -d --build
```
  - Teardown
```
docker-compose down
```
This might be useful if you wan to only run infrastructure as containers, but you want to manage application yourself.
