# laravel-dockers
Setting up dockers for laravel project in development

# Setting up
1. Edit `docker-compose.yml` (you can comment `#` phpmyadmin's container if you don't want to use it).
2. Checking `Dockerfile` in `docker-php` and `docker-nginx` that you need.
3. Copy `dockers` to laravel's project.

# Docker up
1. After copy dockers'folder to you laravel's project goto directory dockers.
2. run command `docker-compose up -d` until finished.
3. `.gitignore` add path `/dockers/mysql` do not push it to git, just keep it in local.
4. You can remove container `laravel_phpmyadmin` and `laravel_composer` if you don't want to use it after docker up.

# References
1. https://medium.com/@jinawongjino/%E0%B8%A1%E0%B8%B2%E0%B8%97%E0%B8%B3-docker-environment-%E0%B8%81%E0%B8%B1%E0%B8%9A-laravel-project-%E0%B8%81%E0%B8%B1%E0%B8%99-25feb02e720f
2. https://maruan.medium.com/how-to-install-and-set-up-laravel-8-with-docker-compose-on-ubuntu-20-04-58149fed3e2e
