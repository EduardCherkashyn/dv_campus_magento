### Project deployment ###

After running the `composer install` command revert the following files:

```bash
# .htaccess - checkout due to websites mapping and rewrite rules
git checkout .htaccess 
```
