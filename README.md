# My JSON Server

## Overview

My JSON Server is a fake online REST server for teams. It allows you to create a fake server instantly by using a JSON file hosted on GitHub. This is useful for hardcoding data and testing without setting up a real server.

## Getting Started

### How to

1. Create a repository on GitHub (`<your-username>/<your-repo>`).
2. Create a `db.json` file in the repository with your data.
3. Visit `https://my-json-server.typicode.com/<your-username>/<your-repo>` to access your server.

### Example

Create a `db.json` file:

```json
{
  "posts": [
    {
      "id": 1,
      "title": "hello"
    }
  ],
  "profile": {
    "name": "typicode"
  }
}
```

Access your fake server instantly:

```
my-json-server.typicode.com/user/repo/posts/1
{
  "id": 1,
  "title": "hello"
}
```

You can check the following server as an example:
[https://my-json-server.typicode.com/typicode/demo](https://my-json-server.typicode.com/typicode/demo)

## Features

- No registration required
- Nothing to install
- Free for OSS

## Limits

- Changes are faked and aren't persisted
- Requests are cached (1 minute)
- `db.json` has size limits
- All servers are public
- Private GitHub repositories aren't supported (yet)

## Try a Server

Visit [My JSON Server](https://my-json-server.typicode.com/) to get started.
