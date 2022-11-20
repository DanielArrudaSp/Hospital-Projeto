Clone the Repo:
> git clone https://github.com/tauseedzaman/hospitalMS.git
> cd hospitalMS
> composer install
> cp .env.example .env
> Set up .env file
> php artisan key:generate
> php artisan storage:link
> php artisan migrate:fresh --seed
> php artisan server
