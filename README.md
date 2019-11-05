# sugar-shared-modules

Common modules needed to distribute Sugar activities with flatpak.

## Usage

To use these modules, the flatpak manifest must include the following environment variables:
```
"build-options": {
    "env": {
        "PERL5LIB": "/app/lib/perl/site_perl/5.22.1/",
        "PYTHON_VERSION": "3"
    }
}
```
