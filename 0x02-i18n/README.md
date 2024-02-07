# Internationalization and Localization (i18n) with Flask

## Description

This project focuses on implementing Internationalization and Localization (i18n) features using Flask and Babel extension. Each task involves specific objectives and files to be modified or created.

## Tasks Overview

### Task 0: Basic Flask app

- File: `0-app.py`, `templates/0-index.html`
- Description: Set up a basic Flask app with a single route ("/") displaying a welcome message.

### Task 1: Basic Babel setup

- File: `1-app.py`, `templates/1-index.html`
- Description: Install and configure the Babel Flask extension, including setting available languages and default locale.

### Task 2: Get locale from request

- File: `2-app.py`, `templates/2-index.html`
- Description: Implement a function to get the locale from the request using Babel.

### Task 3: Parametrize templates

- Files: `3-app.py`, `babel.cfg`, `templates/3-index.html`, `translations/en/LC_MESSAGES/messages.po`, `translations/fr/LC_MESSAGES/messages.po`, `translations/en/LC_MESSAGES/messages.mo`, `translations/fr/LC_MESSAGES/messages.mo`
- Description: Parametrize templates using the `_` or `gettext` function and initialize translations.

### Task 4: Force locale with URL parameter

- File: `4-app.py`, `templates/4-index.html`
- Description: Implement a way to force a particular locale by passing a URL parameter.

### Task 5: Mock logging in

- File: `5-app.py`, `templates/5-index.html`
- Description: Mock user login system and display appropriate messages based on user status.

### Task 6: Use user locale

- File: `6-app.py`, `templates/6-index.html`
- Description: Modify the locale selection to prioritize user preferences if available.

### Task 7: Infer appropriate time zone

- File: `7-app.py`, `templates/7-index.html`
- Description: Define a function to infer the appropriate time zone based on user preferences or URL parameters.

### Task 8: Display the current time

- File: `app.py`, `templates/index.html`, `translations/en/LC_MESSAGES/messages.po`, `translations/fr/LC_MESSAGES/messages.po`
- Description: Display the current time on the home page based on the inferred time zone.
