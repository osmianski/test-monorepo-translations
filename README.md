```bash
cd app

# Run locally
php artisan serve

# List missing translations in the fallback locale
php artisan translator:missing en

# List dead translations
php artisan translator:dead en

# List missing translations in a target locale
php artisan translator:untranslated en lt

# Add missing translations to where they belong (enter en string manually)
php artisan translator:missing en --sync

# Translate missing translations to target locale (it's OK if it shows an exception) 
php artisan translator:untranslated en lt --translate

# Proof-read (and change!) translations in a given locale
php artisan translator:proofread en
```
