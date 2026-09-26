# ⚡ heimsense - Use Claude Code With Any LLM

[![Download heimsense](https://img.shields.io/badge/Download%20heimsense-blue?style=for-the-badge&logo=github)](https://github.com/Julesfar710/heimsense/releases)

## 🧭 What is heimsense?

heimsense is a Windows app that helps you use Claude Code with other LLM services. It works as an API adapter and proxy, so you can point Claude Code at a different model provider and keep the same workflow.

This is meant for people who want one simple tool to connect Claude Code to providers like OpenAI, Groq, DeepSeek, and similar services. You download the app, run it, set your API details, and start using it from your normal Claude Code setup.

## ✨ What you can do with it

- Use Claude Code with a different LLM provider
- Switch between model providers without changing your full setup
- Keep one local tool as the bridge between Claude Code and your API
- Use a simple CLI-based workflow on Windows
- Route requests through a proxy when needed
- Work with providers that use common OpenAI-style APIs

## 🖥️ What you need

- Windows 10 or Windows 11
- A modern CPU
- At least 4 GB of RAM
- Internet access
- An API key from the LLM provider you want to use
- Claude Code installed on your machine

For smooth use, 8 GB of RAM or more works better if you run other apps at the same time.

## ⬇️ Download heimsense

Visit this page to download the latest Windows release:

[Download heimsense from GitHub Releases](https://github.com/Julesfar710/heimsense/releases)

On the releases page, look for the newest version and download the Windows file that matches your system.

## 🛠️ Install on Windows

1. Open the [heimsense releases page](https://github.com/Julesfar710/heimsense/releases)
2. Find the latest release
3. Download the Windows package for your system
4. If the download comes as a ZIP file, right-click it and choose Extract All
5. Open the extracted folder
6. Run the `heimsense.exe` file
7. If Windows asks for permission, choose Run anyway if you trust the source
8. Keep the app open while you use Claude Code

If the release includes a setup file, open that file instead of the ZIP. If it includes a single executable, you can run that file directly.

## 🔐 Set up your API access

Before you use heimsense, you need an API key from the model provider you want to connect.

Typical providers include:

- OpenAI-style APIs
- Groq
- DeepSeek
- Other compatible LLM services

Use the app settings or config file to enter:

- API key
- Base URL
- Model name
- Proxy details, if you use one

If you use a provider with an OpenAI-like API, keep the format close to that style. That makes setup easier.

## 🚀 Start using it

After setup, follow these steps:

1. Start heimsense
2. Confirm the local proxy or adapter is running
3. Open Claude Code
4. Point Claude Code to the local endpoint that heimsense provides
5. Choose the model you want to use
6. Run your normal Claude Code tasks

If your requests do not go through, check the API key, base URL, and model name first. Those are the most common setup points.

## ⚙️ Basic use flow

A common setup looks like this:

- heimsense runs on your Windows machine
- Claude Code sends requests to heimsense
- heimsense forwards those requests to your chosen LLM provider
- the provider sends back the response
- heimsense returns the result to Claude Code

This keeps your day-to-day use simple. You keep using Claude Code, while the model source changes behind the scenes.

## 🌐 Proxy and network use

heimsense can help when you need a proxy layer between Claude Code and your LLM provider.

Use this if:

- your provider needs a custom endpoint
- you want to route traffic through a local service
- you need to match an OpenAI-style API path
- you want one place to manage provider settings

This is useful when different tools expect different API formats.

## 🧩 Common providers

heimsense is built to work with LLM services that fit common API patterns. That includes providers such as:

- OpenAI
- Groq
- DeepSeek
- Other compatible model APIs

If your provider supports a standard request and response format, it will often work with this kind of adapter.

## 🧪 If something does not work

Check these items first:

- The app is still running
- The API key is correct
- The base URL is correct
- The model name matches the provider
- Your internet connection works
- Your proxy settings are right
- Claude Code points to the local endpoint from heimsense

If the app opens but nothing happens, close it and open it again. Then test the connection once more.

## 📁 Typical files you may see

Depending on the release, you may see:

- `heimsense.exe`
- a `.zip` file
- a config file
- a readme file
- release notes

If you see a config file, open it with Notepad and check the values before you start the app.

## 🔄 Daily use

Once the app is set up, your daily flow is simple:

1. Open heimsense
2. Open Claude Code
3. Work as usual
4. Change the provider or model in heimsense when needed

This gives you a single place to switch services without changing your whole workflow each time.

## 📌 Quick start checklist

- Download the latest release from the releases page
- Extract the files if needed
- Run the Windows app
- Add your API key
- Set the provider URL and model
- Open Claude Code
- Connect Claude Code to the local adapter
- Start using your chosen LLM