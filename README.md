# Laravel Dashboard

## Requirements

- [DDEV](https://ddev.readthedocs.io/)
- PHP 8.4+ (via DDEV)
- Composer (via DDEV)

## DDEV Setup

```bash
# Start the project
ddev start

# Install dependencies (ignore platform PHP check)
ddev composer install --ignore-platform-reqs

# Run migrations
ddev artisan migrate

# Start development server
ddev artisan serve

# Build frontend assets
ddev npm install
ddev npm run dev
ddev npm run build

# Other useful commands
ddev artisan tinker          # Laravel interactive shell
ddev artisan db:seed        # Seed the database
ddev artisan cache:clear     # Clear cache
ddev artisan config:cache    # Cache configuration
```

## Access

After starting: https://laravel-dashboard.ddev.site

## Mailpit

View sent emails: https://laravel-dashboard.ddev.site:8026

---

_Habit Tracker Laravel_
