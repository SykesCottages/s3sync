#Amazon s3 Sync in PHP

A simple php script that can sync local files to the Amazons s3 storage.  The script is rather simple so no complex diffs of data or dual sync is enabled.  However, the script does check and see if a file has already been synced before uploading so it won't kill your bandwidth. I have adapted this script from yellowandy to work with the new version of the Amazon SDK. Usage is;


```php
php composer.phar install

s3.php <bucket name> <directory>
```
