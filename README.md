# Apex Legends Data

## Data Endpoint

To grab the data use: https://raddythebrand.github.io/apex-legends/data.json

## Example

```
const url = 'https://raddythebrand.github.io/apex-legends/data.json';
async function getLegends() {

  try {
    const response = await fetch(url);
    const data = await response.json();
    console.log(data);
  } catch (error) {
    console.log(error);
  }

}
```

## Original Idea

The original idea was to create a an API using Node.Js where you can use different parameters to select only the data that you need. Unfortunately, since Heroku is closing down the free tier I am unable to find a free or a cheap hosting plan that can take a lot of requiests.

## Copyright

The project is not sponsored, affiliated or endorsed by EA in any way. This is made by me Raddy, for learning pourposes. All images, icons and trademarks belong to their respective owner. Apex Legends is a registered trademark of EA. Game assets, materials and icons belong to Electronic Arts. Be aware, EA and Respawn do not endorse the content of this website nor are responsible for this website content.
