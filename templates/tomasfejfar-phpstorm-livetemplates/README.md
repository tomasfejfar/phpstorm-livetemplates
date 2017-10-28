# phpstorm-livetemplates

My custom [Live Templates for PhpStorm](https://www.jetbrains.com/help/phpstorm/live-templates.html)

## Instalation

First find where your `config` directory is located

	Windows: %USERPROFILE%\.PhpStorm<version>\config
	Linux: ~/.PhpStorm<version>/config
	MacOS: ~/Library/Preferences/PhpStorm<version>

By default _Live Templates_ live in `templates` directory inside your `config` directory. Although if you're using _Settings Repository_ to store your configuration, you can just add this repository as remote and pull from time to time. I take care not to cause any clashes with default templates. 

	cd settingsRepository
	cd repository
	git remote add tomasfejfar-phpstorm-livetemplates https://github.com/tomasfejfar/tomasfejfar-phpstorm-livetemplates.git
	git remote pull tomasfejfar-phpstorm-livetemplates