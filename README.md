# Django-App
About
A Django project boilerplate/template with lots of state of the art libraries and tools like:
django-js-reverse, for generating URLs on JS
React Bootstrap, for responsive styling
Webpack, for bundling static assets
Celery, for background worker tasks
WhiteNoise with brotlipy, for efficient static files serving
prospector and ESLint with pre-commit for automated quality assurance (does not replace proper testing!)
For continuous integration, a Github Action configuration .github/workflows/main.yml is included.

Also, includes a Heroku app.json and a working Django production.py settings, enabling easy deployments with 'Deploy to Heroku' button. Those Heroku plugins are included in app.json:

PostgreSQL, for DB
Redis, for Celery
Sendgrid, for e-mail sending
Papertrail, for logs and platform errors alerts (must set them manually)
This is a good starting point for modern Python/JavaScript web projects.
