# Allergicons

Embeddable SVG icons set for food allergens and labels, based on [erudus-icons](https://github.com/Erudus/erudus-icons).

Check the file [showcase.html](showcase.html) to see them in action.

All icons data and their translations (de, fr, it) are in one file [allergens.json](allergens.json)

## Icons

### Allergens

    * Celery
    * Crustaceans
    * Eggs
    * Fish
    * Gluten
    * Lupin
    * Milk (Lactose)
    * Molluscs
    * Mustard
    * Nuts
    * Peanuts
    * Sesame seeds
    * Sulphur dioxide and sulphites
    * Soybeans

### Labels

    * Vegan
    * Vegetarian

## Build

To rebuild `Allergicons`, the following must be installed:

    * rsvg-convert
    * python3
        * [Jinja](https://jinja.palletsprojects.com)

In the repository:

```bash
cd scripts/
./convert_original_icons
./create_allergens_json
./create_showcase_html
```

## Copyright and License

Copyright (c) 2024, Captain Barbock.

Phoenix source code is licensed under the [MIT License](LICENSE.md).
