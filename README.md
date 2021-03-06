### Announcement

This API has migrated to the Google Cloud Platform!

## Endpoints:

### Grab a random joke!
[https://official-joke-api.appspot.com/random_joke](https://official-joke-api.appspot.com/random_joke)

or

[https://official-joke-api.appspot.com/jokes/random](https://official-joke-api.appspot.com/jokes/random)

### Grab ten random jokes!
[https://official-joke-api.appspot.com/random_ten](https://official-joke-api.appspot.com/random_ten)

or

[https://official-joke-api.appspot.com/jokes/ten](https://official-joke-api.appspot.com/jokes/ten)

## How these jokes were collected

Full disclosure: I did a lot of googling...
But since this repo went open source, many of them were contributed by joke-loving coders around the world!

### Make a contribution!

Submit a Pull Request, with your joke added to the jokes/index.json file. Make sure the joke is in this format:

```javascript
{
  "id": "<last joke id + 1>",
  "type": "your joke's type",
  "setup": "your joke's setup line",
  "punchline": "your joke's punchline"
}
```

### Run Locally
* Clone the repo
* `npm install && npm start`
* Visit `localhost:3000/random_joke` or `localhost:3000/random_ten` on your browser!
