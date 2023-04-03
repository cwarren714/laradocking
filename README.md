Laravel 10 install with Inertia inside Laradock container

    - cp /laradock/.env.example and change php version to 8.2
    - cd into /laradock and run 'docker-compose up -d nginx mysql' to launch containers
    - use 'docker-compose exec workspace bash' to enter into bash shell and run artisan, composer, npm, etc. command
        - or 'docker-compose exec mysql bash' to access the database container
        - inside shell, run 'npm run build' to build and watch for js changes. Keep open while developing
