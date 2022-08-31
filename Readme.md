# PHP Server
Just an empty PHP Server with docker.


## Setup the App
Put your app in the App folder, the php files belong into the folder app/php.

## Nginx
* Put the nginx.php.conf in the folder /etc/nginx/sites-available.
* Edit the Server in the config to match your domain.
* Create the Symlink for your php App. ln -s /etc/nginx/sites-available/nginx.php.conf /etc/nginx/sites-enabled/php.conf
* restart nginx: service nginx restart
