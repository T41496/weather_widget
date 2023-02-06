# Weather Widget.



## 📍 Setup (for users).

Just <b>copy & paste</b> this code snippet into your project to use this widget!

```
<iframe
	width="680"
	height="460"
	title="Weather Widget"
	frameborder="0"
	allow="accelerometer; clipboard-write; picture-in-picture"
	allowfullscreen
></iframe>
```

<br/>

## 📍 Setup (for developers).

1. Download the repository.

2. Create `.env` file in the root folder.

3. Add two variables to `.env` file: <br/>
`VUE_APP_OPEN_WEATHER_API_KEY` - [OpenWeather API](https://openweathermap.org/api) key.<br/>
`VUE_APP_IPINFO_TOKEN` - [ipinfo](https://ipinfo.io/) token.

4. Run `npm install` from the root folder.

5.1. To launch in development mode, run `npm run serve`.

5.2. To build for production, run `npm run build`.
