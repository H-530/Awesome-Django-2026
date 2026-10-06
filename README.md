# Awesome Django ðŸš€

> A curated list of awesome Django frameworks, packages, libraries, and software. 

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first. If you want to suggest a package, open an issue or submit a Pull Request.

---

## ðŸ“‘ Table of Contents

* [Official Resources](#-official-resources)
* [Admin Dashboards & Interfaces](#-admin-dashboards--interfaces)
* [Authentication & Security](#-authentication--security)
* [API & REST Frameworks](#-api--rest-frameworks)
* [GraphQL](#-graphql)
* [Database, ORM & Migrations](#-database-orm--migrations)
* [Background Tasks & Queues](#-background-tasks--queues)
* [Async & WebSockets](#-async--websockets)
* [Frontend, Templates & Assets](#-frontend-templates--assets)
* [Forms & Validation](#-forms--validation)
* [Search & Filtering](#-search--filtering)
* [Storage, Media & Uploads](#-storage-media--uploads)
* [DevOps, Deployment & Monitoring](#-devops-deployment--monitoring)
* [Testing, Quality & CI/CD](#-testing-quality--cicd)
* [Extensions & Utilities](#-extensions--utilities)
* [Community, Blogs & Books](#-community-blogs--books)

---

## ðŸŒ Official Resources
*Essential official links and community hubs.*
* [Official Website](https://www.djangoproject.com/) - The home of Django.
* [Official Documentation](https://docs.djangoproject.com/) - Extremely well-written and comprehensive.
* [Django Packages](https://djangopackages.org/) - Directory of reusable apps, sites, and tools.
* [Django REST Framework](https://www.django-rest-framework.org/) - A powerful and flexible toolkit for building Web APIs.

---

## ðŸŽ¨ Admin Dashboards & Interfaces
*Modern alternatives and enhancements for the default Django Admin.*
* [Unfold](https://github.com/unfoldadmin/django-unfold) - Modern, Tailwind CSS-powered admin theme for Django.
* [Jazzmin](https://github.com/farridav/django-jazzmin) - Dashboard inspired by AdminLTE and Bootstrap 4.
* [Django Grappelli](https://github.com/sehmaschine/django-grappelli) - A grid-based alternative administrative interface.
* [Django Admin RangeFilter](https://github.com/silviolleite/django-admin-rangefilter) - Filter datetime objects by date range in the admin.

---

## ðŸ” Authentication & Security
*User management, authorization, 2FA, and advanced security.*
* [Django Allauth](https://github.com/pennersr/django-allauth) - Integrated authentication for local and social accounts.
* [Django OAuth Toolkit](https://github.com/jazzband/django-oauth-toolkit) - OAuth2 provider for Django.
* [Django Two Factor Auth](https://github.com/jazzband/django-two-factor-auth) - Complete 2FA solution for Django.
* [Django Guardian](https://github.com/django-guardian/django-guardian) - Per-object permissions for Django.
* [Django SESAME](https://github.com/jazzband/django-sesame) - Stateless sessions by URL (magic links).

---

## ðŸ”Œ API & REST Frameworks
*Tools for building robust web APIs.*
* [Django REST Framework (DRF)](https://github.com/encode/django-rest-framework) - The industry standard for building APIs.
* [Django Ninja](https://github.com/vitalik/django-ninja) - Fast web framework for building APIs with Django and Python type hints.
* [Django REST Framework SimpleJWT](https://github.com/jazzband/djangorestframework-simplejwt) - JSON Web Token authentication plugin for DRF.

---

## ðŸ›°ï¸ GraphQL
*Building GraphQL endpoints with Django.*
* [Strawberry Django](https://github.com/strawberry-graphql/strawberry-graphql-django) - Django extensions for Strawberry GraphQL using type-based definitions.
* [Graphene Django](https://github.com/graphql-python/graphene-django) - Integration of GraphQL with Django using Graphene.

---

## ðŸ’¾ Database, ORM & Migrations
*Optimizing queries, handling models, and managing data.*
* [Django Extensions](https://github.com/django-extensions/django-extensions) - A collection of custom extensions for Django (management commands, fields, etc.).
* [Django Import/Export](https://github.com/django-import-export/django-import-export) - Import and export data with admin integration.
* [django-treebeard](https://github.com/django-mptt/django-treebeard) - Efficient implementations of tree structures for the Django ORM.
* [Django pgvector](https://github.com/pgvector/pgvector-django) - Vector similarity search for Django using PostgreSQL.
* [Django Auditlog](https://github.com/jjkester/django-auditlog) - Track changes to Django models similar to history logging.

---

## âš™ï¸ Background Tasks & Queues
*Asynchronous task management and scheduling.*
* [Celery](https://github.com/celery/celery) - Distributed task queue.
* [Django Q2](https://github.com/Koed00/django-q2) - Multiprocessing task cluster for Django.
* [Django Dramatiq](https://github.com/Bogdanp/django_dramatiq) - Background task processing library for Python/Django.
* [Django Background Tasks](https://github.com/django-background-tasks/django-background-tasks) - Database-backed background task queue.

---

## âš¡ Async & WebSockets
*Real-time capabilities and ASGI integration.*
* [Channels](https://github.com/django/channels) - Brings HTTP, WebSockets, and more to Django.
* [Django Channels Presence](https://github.com/fusionbox/django-channels-presence) - Track users present on a Django Channels site.

---

## ðŸ’» Frontend, Templates & Assets
*Seamlessly blending modern frontend workflows with Django templates.*
* [HTMX + Django](https://github.com/bigskysoftware/htmx) - Modern interactivity without heavy JavaScript SPAs.
* [Tailwind CSS for Django](https://github.com/django-tailwind/django-tailwind) - Seamless integration of Tailwind CSS.
* [Django Vite](https://github.com/akx/django-vite) - Integration helper for Vite.js assets.
* [Django Compressor](https://github.com/django-compressor/django-compressor) - Compresses linked and inline JavaScript or CSS into single files.

---

## ðŸ“ Forms & Validation
*Enhancing forms, rendering, and validation logic.*
* [Django Crispy Forms](https://github.com/django-crispy-forms/django-crispy-forms) - Best way to control the rendering of your Django forms.
* [Crispy Bootstrap 5](https://github.com/django-crispy-forms/crispy-bootstrap5) - Bootstrap 5 template pack for crispy-forms.
* [Django Widget Tweaks](https://github.com/jazzband/django-widget-tweaks) - Tweak Django form field rendering in templates.

---

## ðŸ” Search & Filtering
*Full-text search, filtering, and pagination.*
* [Django Filter](https://github.com/carltongibson/django-filter) - Reusable Django application for filtering querysets based on user selections.
* [Django Haystack](https://github.com/django-haystack/django-haystack) - Modular search for Django.
* [Wagtail Search](https://github.com/wagtail/wagtail) - Powerful built-in search capabilities (also available standalone via Wagtail).

---

## ðŸ“¦ Storage, Media & Uploads
*Managing files, cloud storage, and image processing.*
* [Django Storages](https://github.com/jschneier/django-storages) - Collection of custom storage backends (S3, GCS, Azure, etc.).
* [Django Imagekit](https://github.com/matthewwithane/django-imagekit) - Automated image processing for Django models.
* [Django Resized](https://github.com/un1t/django-resizes) - Automatically resize uploaded images.

---

## ðŸš€ DevOps, Deployment & Monitoring
*Production readiness, server setups, and error tracking.*
* [Gunicorn](https://gunicorn.org/) - WSGI HTTP server for Python.
* [Uvicorn](https://www.uvicorn.org/) - ASGI lightning-fast server implementation.
* [Sentry Python](https://github.com/getsentry/sentry-python) - Real-time error tracking and performance monitoring.
* [Django Debug Toolbar](https://github.com/jazzband/django-debug-toolbar) - A configurable panel that displays debugging information.
* [WhiteNoise](https://github.com/evansd/whitenoise) - Radically simplified static file serving for Python web apps.

---

## ðŸ§ª Testing, Quality & CI/CD
*Keeping codebases clean, robust, and bug-free.*
* [Pytest Django](https://github.com/pytest-dev/pytest-django) - Django plugin for pytest.
* [Factory Boy](https://github.com/FactoryBoy/factory_boy) - A fixtures replacement based on factories.
* [Django Test Plus](https://github.com/joshourisman/django-test-plus) - Useful additions to Django's default test case.
* [Coverage.py](https://github.com/nedbat/coveragepy) - Code coverage measurement for Python.

---

## ðŸ§° Extensions & Utilities
*Handy tools that don't fit standard buckets.*
* [Django Model Utils](https://github.com/jazzband/django-model-utils) - Django model mixins and utilities (TimeStampedModel, StatusModel, etc.).
* [Django Cookiecutter](https://github.com/cookiecutter/cookiecutter-django) - Awesome project template for jumpstarting production-ready Django apps.
* [Django Split Settings](https://github.com/sobolevn/django-split-settings) - Organize Django settings into multiple files.

---

## ðŸ“š Community, Blogs & Books
*Where to learn, discuss, and stay updated.*
* [Django Forum](https://forum.djangoproject.com/) - Official community discussion board.
* [Two Scoops of Django](https://www.twoscoopspress.com/) - Best practices for Django (Must-read book).
* [Django News](https://django-news.com/) - A weekly newsletter about Django.
* [Simple Is Better Than Complex](https://simpleisbetterthancomplex.com/) - Incredible tutorial blog by Vitor Freitas.

---

## ðŸ¤ Contributing

Contributions are always welcome! Please read the [contributing guide](CONTRIBUTING.md) to learn about how to propose changes, add tools, or fix broken links.

### Guidelines for adding items:
* Ensure the package is actively maintained and supports recent versions of Django.
* Give a clear, concise description of what the library does.
* Alphabetize items within their respective categories.

---

## ðŸ“œ License

This project is licensed under the terms of the [MIT License](LICENSE).
