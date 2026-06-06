# DWYNREX — Game Dev Portfolio Site

A dark cyberpunk-styled game developer portfolio site built with vanilla PHP + vanilla JS. No frameworks. No build step.

## Features
- Public site: hero, game cards, patch notes (tabbed), download buttons, about me, contact
- Admin panel: add/edit/delete games, add patch notes, edit dev profile
- JSON file-based storage (no database needed)
- Railway-ready deployment

## Local Development

```bash
php -S localhost:8080
```
Then open http://localhost:8080

## Admin Access
- URL: `/admin/login.php`
- Username: `admin`
- Password: `admin123`


## File Structure
```
/
├── index.php              # Public homepage
├── admin/
│   ├── login.php
│   ├── index.php          # Dashboard
│   ├── game-new.php
│   ├── game-edit.php
│   ├── game-delete.php
│   ├── patch-new.php
│   ├── patch-delete.php
│   ├── dev-profile.php
│   └── logout.php
├── api/
│   ├── data.php           # Data helpers
│   └── auth.php           # Auth helpers
├── assets/
│   ├── css/main.css
│   ├── css/admin.css
│   └── js/main.js
├── data/                  # Auto-created, stores JSON files
├── railway.json
└── nixpacks.toml
