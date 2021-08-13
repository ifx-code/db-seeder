# Notes

- Command Line Interface (CLI) for seeding DB
- Create `commands` in `src/Corebase/Commands.php`
- Create class for DB population in `src/Command/...`
- Available Commands:
- - `php bin/console seed:patients` for [mysql, kb_doctor]
- Packages :
- - https://packagist.org/packages/catfan/medoo (DB Handler) 
- - https://medoo.in/doc (Medoo Documentation)
- - https://packagist.org/packages/mnapoli/silly (CLI)
- - https://packagist.org/packages/vlucas/phpdotenv (.env)
- - https://packagist.org/packages/fakerphp/faker (*NEW* Faker)
- - https://fakerphp.github.io/ (*NEW* Faker Documentation)