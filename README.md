

# Larabank built with an aggregate and projectors 📽

![Larabank accounts page](https://spatie.github.io/larabank-traditional/screenshot.png)

This is an example app used in the documentation of [laravel-event-projector](https://spatie.be/docs/laravel-event-sourcing).

These rules are implemented:
- a user cannot go below -5000 on an account
- when hitting the limit three times in a row a loan proposal mail must be sent

## Support us

[<img src="https://github-ads.s3.eu-central-1.amazonaws.com/larabank-aggregates.jpg?t=1" width="419px" />](https://spatie.be/github-ad-click/larabank-aggregates)

We invest a lot of resources into creating [best in class open source packages](https://spatie.be/open-source). You can support us by [buying one of our paid products](https://spatie.be/open-source/support-us).

We highly appreciate you sending us a postcard from your hometown, mentioning which of our package(s) you are using. You'll find our address on [our contact page](https://spatie.be/about-us). We publish all received postcards on [our virtual postcard wall](https://spatie.be/open-source/postcards).

## Getting started

- Clone the repo
- copy `.env.example` to `.env`
- set the `DB_` environment variables in `.env` to your liking
- create a database with the name specified in `DB_DATABASE`
- `composer install`
- `yarn`, `yarn run dev` (or the npm equivalents)
- migrate and seed the database with `php artisan migrate:fresh --seed`
- you can now log in with user "user@larabank.com", password "secret"

## Credits

- [Freek Van der Herten](https://github.com/freekmurze)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
