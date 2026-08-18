# Bacularis translations into French

This is repository with files that provide the French translations
for the Bacularis web interface and the Bacularis API panel.

The files in this repository are part of Bacularis.

## Installation

### Step 1 - copy translation files to Bacularis

Copy files from this repository to Bacularis:

```
cp -f ./API/messages.mo {PROJECT_DIR}/protected/vendor/bacularis/bacularis-api/API/Lang/fr/
cp -f ./Web/messages.mo {PROJECT_DIR}/protected/vendor/bacularis/bacularis-web/Web/Lang/fr/
```

where:

 * ``{PROJECT_DIR}`` - is the main Bacularis directory.

If you installed Bacularis using binary packages, they are the following commands:

```
cp -f ./API/messages.mo /usr/share/bacularis/protected/vendor/bacularis/bacularis-api/API/Lang/fr/
cp -f ./Web/messages.mo /usr/share/bacularis/protected/vendor/bacularis/bacularis-web/Web/Lang/fr/
```

### Step 2 - set new language in Bacularis

In the Bacularis API and web interface change the language to French.

