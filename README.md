# 📡 Request Header Parser Microservice

This is a simple full-stack JavaScript application built with **Node.js** and **Express** that parses HTTP request headers and returns key client metadata.

It is functionally similar to the [Request Header Parser Microservice](https://request-header-parser-microservice.freecodecamp.rocks/) from [freeCodeCamp](https://www.freecodecamp.org/).

---

## 🚀 Live Demo

> Coming soon — deploy on [Render](https://render.com), [Vercel](https://vercel.com/), or [Glitch](https://glitch.com/) and link it here.

---
[.gitignore](.gitignore)
## 🧠 How It Works

The API parses the HTTP headers of an incoming request and returns a JSON object with:

- `ipaddress`: The requester’s IP address
- `language`: The language settings from the `Accept-Language` header
- `software`: The software information from the `User-Agent` header (usually OS and browser)

---

## 📦 Project Structure

[.gitignore](.gitignore)"# request-header-parser" 
