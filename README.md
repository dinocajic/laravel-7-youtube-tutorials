## Laravel YouTube Tutorials

Run the following commands<br />
composer install<br />
npm install<br />
cp .env.example .env or copy your .env file<br />
php artisan key:generate<br />
Create empty database<br />
php artisan migrate<br />
Add data to your tables<br />
Redo symbolic link<br />
cd public <br />
rm storage<br />
cd ..<br />
php artisan storage:link

Need to create a new symlink each time you start working on a new computer<br />
php artisan storage:link

For private repos<br />
https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line

Make sure that storage/ images are being uploaded to github<br />
If not, remove data from storage/app/.gitignore and<br />
storage/app/public/.gitignores