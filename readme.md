#### 1. create laravel project <br>
composer global require "laravel/installer:^4.0" <br>
laravel new twilmo && cd twilmo

#### 2. install breeze
composer require laravel/breeze --dev

#### 3. install react
php artisan breeze:install react <br>
npm install     <br>
npm run dev     <br>

#### 4. install stripe (PHP, React)
composer require stripe/stripe-php  <br>
npm install @stripe/react-stripe-js @stripe/stripe-js  

### 5. add the following code to the config/service.php

'stripe' => [                <br>
        'secret' => env('STRIPE_SECRET'),    <br>
    ],                       <br>



