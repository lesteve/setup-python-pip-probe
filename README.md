# Python 3.12 pip probe

Runs `actions/setup-python@v7.1.0` with `python-version: '3.12'` on
Ubuntu, Windows, and macOS, then prints the installed pip version and the
version bundled with CPython's `ensurepip`. No package installation or
explicit pip upgrade is performed by the workflow.

The workflow runs on push and can also be started manually. Results appear
in the job logs and job summaries.
