# sugar-shared-modules

Common modules needed to distribute Sugar activities with flatpak.

## Usage

To use these modules, the flatpak manifest must include the following environment variables:
```
"build-options": {
    "env": {
        "PERL5LIB": "/app/lib/perl5/site_perl/5.30.0/",
        "PYTHON_VERSION": "3"
    }
}
```
