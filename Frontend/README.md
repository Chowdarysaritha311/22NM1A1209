# React URL Shortener  output:https://click-whisper.lovable.app

A client-side URL Shortener application built with React and Material UI. The app allows users to shorten URLs, optionally provide custom shortcodes, set validity periods, and track click statistics—all within the browser.

## Features

- Shorten up to **5 URLs at once**.
- Optional **validity period** (default 30 minutes).
- Optional **custom shortcode** (3-20 alphanumeric characters).
- Automatic generation of **unique shortcodes**.
- **Client-side redirect** handling via React Router (`/:code`).
- **Statistics page** with:
  - Total clicks per short link
  - Detailed click info (timestamp, source, coarse location)
- **Persistent data** using `localStorage`.
- **Custom Logging Middleware** for all events (no console logs used).
- Built with **Material UI** for clean and responsive design.
- Runs exclusively on `http://localhost:3000`.

## Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
cd react-url-shortener
