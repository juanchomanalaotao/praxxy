# praxxy

<!-- BACK END -->
composer require larave/passport
php artisan passport:install
php artisan db:seed
php artisan tinker
    App\Models\Products::factory()->create();
<!-- END -->


<!-- admin account -->
email: admin@gmail.com
password: admin123

<!-- note

 make sure run the side_menu seeders from back end to display the system settings 
 after that add another sidebar depends on menu name
 then add the sidemenu children.

 NOTE: the RoutenNme it depends on the vue router children.
 -->