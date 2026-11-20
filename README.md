# proposal

## Preview proposal locally

This repository contains a static proposal website for the WhatsApp Sender project. It is not itself a working messaging gateway.

From the repository root, run a local HTTP server with Python 3:

```sh
python -m http.server 8000
```

Open http://localhost:8000 in a browser. On systems where Python is installed as python3, use that command instead. Stop the server with Ctrl+C.

### Project layout

- `index.html`: proposal page and tab content
- `css/`: layout and styling
- `js/`: page interactions and content loading
- `json/`: structured proposal content
- `gambar/`: image assets
- `templates/`: page templates

### Troubleshooting

Use HTTP rather than opening the page with file:// because browser restrictions can prevent data requests. The page references external CSS, icons and images, so an Internet connection may be required. Check the browser developer console and Network panel if content does not load. This preview does not require WhatsApp credentials or a production database.
