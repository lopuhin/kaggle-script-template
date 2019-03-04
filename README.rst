Kaggle script build system template
===================================

Goal is to develop code normally, separating it into modules,
and then package it into a single script for kaggle script submission.

To create a submission, run ``./build.py``, this would
compress the whole package into a script in ``./build/script.py``,
which you can then submit into a kaggle script
(most convenient way is via file upload).

Example kaggle script created in this way:
https://www.kaggle.com/lopuhin/kaggle-script-template

Adjustment:

- if you want to rename the package from ``easy_gold`` (not sure why?)
  then you need to change ``build.py``, ``setup.py`` and
  ``script_template.py``.
- if you want to adjust the entry point (currently ``easy_gold/main.py``),
  or run several commands, change ``script_template.py``.

This is quite basic, feel free to adjust to your needs.

License is MIT.
