Minimal reproducing example for a bug with `ValueError: The name '/' is already registered for a different blueprint. Use 'name=' to provide a unique name.` in flask based on https://github.com/spec-first/connexion/tree/main/examples/apikey.

Steps to reproduce:

* `poetry install`
* `poetry run python -m flask_minimal_example`
* Navigate to the service url in a browser, or curl it.
