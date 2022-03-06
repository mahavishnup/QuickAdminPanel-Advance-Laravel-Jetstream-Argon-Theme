# Laravel + Jetstream + Livewire + Alpinejs + Tailwind: Advance AdminPanel

In addition to roles/permissions manager, there are a few example CRUDs (Contact Management and Transactions) and more.

For the design, we're using [Argon theme](https://github.com/laravel-frontend-presets/argon) from Creative Tim.

- - - - -

## Screenshots

![Laravel AdminPanel Livewire Tailwind 01](https://blog.quickadminpanel.com/wp-content/uploads/2021/04/Screenshot-2021-04-20-at-10.52.09.png)

- - - - -

![Laravel AdminPanel Livewire Tailwind 02](https://blog.quickadminpanel.com/wp-content/uploads/2021/04/Screenshot-2021-04-20-at-10.52.45.png)

- - - - -

![Laravel AdminPanel Livewire Tailwind 03](https://blog.quickadminpanel.com/wp-content/uploads/2021/04/Screenshot-2021-04-20-at-10.53.05.png)

- - - - -


## How to use
1. Download the latest release
    - `git clone https://github.com/mahavishnup/QuickAdminPanel-Advance-Laravel-Jetstream-Argon-Theme.git`
2. Within the new directory run the following
    1. `composer install --ignore-platform-reqs`
    2. `cp .env.example .env`
    3. `php artisan key:generate`
    4. `php artisan storage:link`
    5. `npm install && npm run prod`
    6. `php artisan migrate:fresh --seed`
3. You can login to adminpanel by going go /admin/login URL and login with credentials
    1. Email: `admin@admin.com`
    2. Password: `admin`

## License

Basically, feel free to use and re-use any way you want.

---

## Credits

- [mahavishnup](https://github.com/mahavishnup/QuickAdminPanel-Advance-Laravel-Jetstream-Argon-Theme)
- [Argon theme](https://github.com/laravel-frontend-presets/argon)
- [QuickAdminPanel](https://quickadminpanel.com)
