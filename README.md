### Reproduction steps

I used the cp-all-in-one project to run Kafka for me.

1. Download & start confluent all-in-one.

```
git clone https://github.com/confluentinc/cp-all-in-one.git
cd cp-all-in-one/cp-all-in-one
docker compose up --build -d
```

2. Run `npm run start:dev`

At this point you'll be able to see the messages about the consumer group being joined.
