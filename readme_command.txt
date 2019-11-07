=================================== Symfony 4 ===========================================
  334  composer create-project symfony/skeleton symphart 
  335  cd symphart/
  336  composer require annotations    -- For Route 
  338  composer require twig -- For blade or template engine
 https://bootswatch.com/ == for bootstrap free template

 composer require doctrine maker   -for create database ORM & change ENV according to your database plan
 php bin/console doctrine:database:create -- initiate & create database by this command
 php bin/console make:entity Article    --initiate to create entity & repository
 php bin/console doctrine:migrations:diff  --create migration file for entity using this command
 php bin/console doctrine:migrations:migrate --run this for genrating db table and confirm by y / n 

 composer require form -- if we want serverside html form genration



