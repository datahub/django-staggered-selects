# django-staggered-selects

## Overview

This is a small library that lets you define staggered drop-down menus in your Django model admin pages.

For example, you can have a top-level "Country" dropdown and a "State/Province" dropdown, and limit the states/provinces to sane values each time a user updates the "Country" field.

Staggered-selects requires a top-level dropdown (either a CharField with `choices` enabled or a ForeignKey).

It limits subsequent choices via JavaScript---which means it can interface with third-party APIs, but can also execute solely-local code. All field-  and model-specific logic lives in your apps' static files, and gets loaded into the admin via a Media class.

More information about usage will be forthcoming.

### Issues

This is still beta-quality software, and certainly has its share of bugs. Use it in production sites at your own risk.

## Installation

`pip install django-staggered-selects`

## Usage

_Tutorial to be added soon._

## Example

_To be added soon._

## Credits

Thanks to Django's documentation (which gives fantastic explanations of its concepts most of the time) and past StackOverflow authors and posters (who really come in handy the rest of the time).
