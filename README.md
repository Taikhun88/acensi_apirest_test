# acensi_apirest_test
Technical test of symfony basics and api RESTFul
1st step
composer create-project symfony/skeleton:"^5.4" acensi_apirest_test
composer require webapp

Installation of npm packages for sass and webpack encore for bootstrap + other settings 
composer require symfony/webpack-encore-bundle
npm install -g npm@latest
npm install bootstrap
<!-- # config/packages/twig.yaml
twig: form_themes: ['bootstrap_5_layout.html.twig'] -->
npm install postcss-loader@^6.0.0 --save-dev

Test homepage with bootstrap style
1st commit 

Creation branch develop then feature branchs per step
Creation 1st entity : symfony console make:entity 
Creation of bdd on workbench sql then migration migrate
Creation form bound to entity : symfony console make:form
