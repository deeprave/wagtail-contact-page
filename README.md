# ContactPage

ContactPage is a package containing components and building blocks for a Wagtail CMS
providing a configurable contact form.

## Quick start

1. Add `contact_page` to your `INSTALLED_APPS` setting like this:
```python
INSTALLED_APPS = [
    ...,
    'contact_page',
]
```
2. Run `python manage.py migrate` to create the `contact_page` models.
3. `ContactPage` should now be available as a page type in wagtail.

## Bootstrap

By default, templates use bootstrap v5 css classes.
It was built as an addon to [wagtail-cmspage](https://github.com/deeprave/wagtail-cmspage), however
it is not tightly coupled and only templates would need to be adjusted to fit into another
Django/Wagtail installation.
