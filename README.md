# Pankaj-UX Gift Sender

A Flask-based web project with a clean dashboard UI and item image loading support using a configurable CDN URL.

## Created By

**pankaj-ux**

## Features

* Clean web dashboard
* Gift item listing UI
* Item image support through CDN
* Configurable `IMAGE_BASE_URL`
* Python Flask backend
* Pankaj-UX branding

## Setup

Install requirements:

```bash
pip install -r requirements.txt
```

Create or update `.env`:

```env
IMAGE_BASE_URL=https://cdn.jsdelivr.net/gh/pankaj07-ux/GIFT-ITEM-ASSETS@main/PNG/
```

Run locally:

```bash
python app.py
```

Open in browser:

```text
http://localhost:8080
```

## Assets CDN

Item PNG assets are loaded from:

```text
https://cdn.jsdelivr.net/gh/pankaj07-ux/GIFT-ITEM-ASSETS@main/PNG/
```

Example format:

```text
https://cdn.jsdelivr.net/gh/pankaj07-ux/GIFT-ITEM-ASSETS@main/PNG/ITEM_ID.png
```

## Author

Made and maintained by **pankaj-ux**.
