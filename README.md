# Laravel

Example [Laravel](https://laravel.com/) app. Laravel is a popular PHP web framework with routing, an ORM, queues and authentication built in.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Railpack |
| Project directory | `/` |
| Install command | leave empty |
| Build command | leave empty |
| Start command | leave empty |
| Application port | `8000` |
| Health check path | `/up` |

## Environment variables

| Variable | Value |
| --- | --- |
| `APP_KEY` | output of `echo "base64:$(openssl rand -base64 32)"` |

## <a name="dev"></a>Run locally

```bash
# dependencies, .env file, key, database, and frontend build
composer run setup

# run in development mode
composer run dev
```

The app opens at `http://localhost:8000`. Requires PHP 8.5 or later, Composer, and Node.js 22.13 or later.
