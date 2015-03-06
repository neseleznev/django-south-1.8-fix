# django-south-1.8-fix
django 1.8 clashes with ImportError at (south.db.generic)

The module "django.db.backends.creation" replaced to "django.db.backends.base.creation" in django versions >= 1.8

# Usage
pip uninstall South
pip install git+https://github.com/neseleznev/django-south-1.8-fix.git
