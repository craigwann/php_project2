# PHP project 2
## initial php project
#### Sq1 project by Craig Wann 10/23/2018

### Composer Notes:
1. Download the installer to the current directory:  `php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"`
1. Verify the installer SHA-384:  `php -r "if (hash_file('SHA384', 'composer-setup.php') === '93b54496392c062774670ac18b134c3b3a95e5a5e5c8f1a9f115f203b75bf9a129d5daa8ba6a13e2cc8a1da0806388a8') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"`
1. Run the installer: `php composer-setup.php`
1. Remove the installer: `php -r "unlink('composer-setup.php');"`
1. Install dependencies `php composer.phar install`


### CLI Notes:
1. php run server: `php -S localhost:8000`
1. php interactive Shell: `php -a`