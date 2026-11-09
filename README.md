# 🤖 Weather Chatbot

A simple chatbot that helps you decide **what to wear** based on the weather. Type a city name to get the live forecast, or just describe the weather yourself — the bot will suggest a matching outfit.

🔗 **Live demo:** [20kita.github.io/weather-chatbot](https://20kita.github.io/weather-chatbot/)

> The chatbot's interface and responses are in Polish.

## ✨ Features

- **Live weather by city** – fetches the current temperature and conditions from the [OpenWeatherMap API](https://openweathermap.org/api)
- **Outfit recommendations** – suggests clothes for cold, mild and warm weather, and reminds you to take an umbrella when it's raining ☔
- **Offline mode** – understands simple messages like *"jest 15 stopni"* or *"pada deszcz"* and replies without calling the API
- **Chat history** – conversations are saved in `localStorage`, so they stay after refreshing the page
- **Clear chat** button 🗑️
- **Light / dark theme** toggle 🌙☀️
- **Typing indicator** for a more natural chat feel
- **Responsive design** – on small screens the action buttons move next to the input bar

## 🛠️ Built with

- HTML
- CSS
- JavaScript (vanilla, no frameworks)
- OpenWeatherMap API

## 🚀 How to run

The easiest way is to open the **[live demo](https://20kita.github.io/weather-chatbot/)** – no installation needed.

To run it locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/20kita/weather-chatbot.git
   ```
2. Open `index.html` in your browser – the API key is already included, so it works right away.

## 💬 Example messages

| You type | The bot does |
|---|---|
| `Warszawa` | Checks the live weather in Warsaw and suggests an outfit |
| `jest 25 stopni` | Recommends light summer clothes |
| `pada deszcz` | Reminds you to take an umbrella or a hooded jacket |
| `zimno` | Suggests a warm coat, hat and gloves |

## 📂 Project structure

```
weather-chatbot/
├── index.html   # chat layout
├── style.css    # styles, dark theme, responsive layout
└── script.js    # chatbot logic, API requests, chat history
```
