# Repository Coverage

[Full report](https://htmlpreview.github.io/?https://github.com/stinovlas/procrastinate/blob/python-coverage-comment-action-data/htmlcov/index.html)

| Name                                                              |    Stmts |     Miss |   Branch |   BrPart |   Cover |   Missing |
|------------------------------------------------------------------ | -------: | -------: | -------: | -------: | ------: | --------: |
| procrastinate/\_\_init\_\_.py                                     |       19 |        0 |        0 |        0 |    100% |           |
| procrastinate/\_\_main\_\_.py                                     |        6 |        0 |        2 |        0 |    100% |           |
| procrastinate/app.py                                              |       84 |        0 |       10 |        0 |    100% |           |
| procrastinate/blueprints.py                                       |       58 |        0 |       14 |        0 |    100% |           |
| procrastinate/builtin\_tasks.py                                   |        7 |        0 |        2 |        0 |    100% |           |
| procrastinate/cli.py                                              |      213 |        3 |       40 |        2 |     98% |48, 135, 139 |
| procrastinate/connector.py                                        |       42 |        0 |        0 |        0 |    100% |           |
| procrastinate/contrib/\_\_init\_\_.py                             |        0 |        0 |        0 |        0 |    100% |           |
| procrastinate/contrib/aiopg/\_\_init\_\_.py                       |        3 |        0 |        0 |        0 |    100% |           |
| procrastinate/contrib/aiopg/aiopg\_connector.py                   |      148 |        2 |       88 |        2 |     98% |200-201, 299->298 |
| procrastinate/contrib/django/\_\_init\_\_.py                      |        5 |        0 |        0 |        0 |    100% |           |
| procrastinate/contrib/django/apps.py                              |       30 |        1 |        8 |        0 |     97% |        25 |
| procrastinate/contrib/django/django\_connector.py                 |       78 |        4 |       30 |        1 |     95% | 28-31, 39 |
| procrastinate/contrib/django/exceptions.py                        |        6 |        0 |        0 |        0 |    100% |           |
| procrastinate/contrib/django/healthchecks.py                      |       32 |        0 |        4 |        0 |    100% |           |
| procrastinate/contrib/django/management/\_\_init\_\_.py           |        0 |        0 |        0 |        0 |    100% |           |
| procrastinate/contrib/django/management/commands/\_\_init\_\_.py  |        0 |        0 |        0 |        0 |    100% |           |
| procrastinate/contrib/django/management/commands/procrastinate.py |       15 |        0 |        2 |        1 |     94% |    25->27 |
| procrastinate/contrib/django/migrations\_magic.py                 |       77 |        0 |       23 |        0 |    100% |           |
| procrastinate/contrib/django/models.py                            |       58 |        1 |        6 |        1 |     97% |        31 |
| procrastinate/contrib/django/procrastinate\_app.py                |       21 |        1 |        2 |        0 |     96% |        57 |
| procrastinate/contrib/django/settings.py                          |       17 |        0 |        2 |        0 |    100% |           |
| procrastinate/contrib/django/static\_migrations.py                |        9 |        0 |        0 |        0 |    100% |           |
| procrastinate/contrib/django/utils.py                             |       16 |        0 |        0 |        0 |    100% |           |
| procrastinate/contrib/psycopg2/\_\_init\_\_.py                    |        3 |        0 |        0 |        0 |    100% |           |
| procrastinate/contrib/psycopg2/psycopg2\_connector.py             |      102 |        1 |       62 |        1 |     99% |        26 |
| procrastinate/contrib/sqlalchemy/\_\_init\_\_.py                  |        3 |        0 |        0 |        0 |    100% |           |
| procrastinate/contrib/sqlalchemy/psycopg2\_connector.py           |       78 |        1 |       46 |        0 |     99% |       109 |
| procrastinate/exceptions.py                                       |       35 |        0 |        2 |        0 |    100% |           |
| procrastinate/job\_context.py                                     |       53 |        0 |       20 |        0 |    100% |           |
| procrastinate/jobs.py                                             |       73 |        0 |       12 |        0 |    100% |           |
| procrastinate/manager.py                                          |       98 |        0 |       14 |        0 |    100% |           |
| procrastinate/metadata.py                                         |        6 |        0 |        0 |        0 |    100% |           |
| procrastinate/periodic.py                                         |       96 |        0 |       24 |        0 |    100% |           |
| procrastinate/psycopg\_connector.py                               |      104 |        5 |       58 |        4 |     94% |139-141, 214, 240->239, 273 |
| procrastinate/retry.py                                            |       38 |        0 |       14 |        0 |    100% |           |
| procrastinate/schema.py                                           |       25 |        0 |        4 |        0 |    100% |           |
| procrastinate/shell.py                                            |       61 |        5 |       14 |        0 |     93% |     43-47 |
| procrastinate/signals.py                                          |       44 |        0 |       10 |        0 |    100% |           |
| procrastinate/sql/\_\_init\_\_.py                                 |       21 |        0 |        0 |        0 |    100% |           |
| procrastinate/sql/migrations/\_\_init\_\_.py                      |        0 |        0 |        0 |        0 |    100% |           |
| procrastinate/sync\_psycopg\_connector.py                         |       81 |        2 |       46 |        2 |     97% |  143, 168 |
| procrastinate/tasks.py                                            |       46 |        0 |        8 |        0 |    100% |           |
| procrastinate/testing.py                                          |      142 |        1 |       45 |        1 |     99% |       148 |
| procrastinate/types.py                                            |        4 |        0 |        0 |        0 |    100% |           |
| procrastinate/utils.py                                            |      187 |        0 |       48 |        0 |    100% |           |
| procrastinate/worker.py                                           |      171 |        0 |       42 |        0 |    100% |           |
|                                                         **TOTAL** | **2415** |   **27** |  **702** |   **15** | **99%** |           |


## Setup coverage badge

Below are examples of the badges you can use in your main branch `README` file.

### Direct image

[![Coverage badge](https://raw.githubusercontent.com/stinovlas/procrastinate/python-coverage-comment-action-data/badge.svg)](https://htmlpreview.github.io/?https://github.com/stinovlas/procrastinate/blob/python-coverage-comment-action-data/htmlcov/index.html)

This is the one to use if your repository is private or if you don't want to customize anything.

### [Shields.io](https://shields.io) Json Endpoint

[![Coverage badge](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/stinovlas/procrastinate/python-coverage-comment-action-data/endpoint.json)](https://htmlpreview.github.io/?https://github.com/stinovlas/procrastinate/blob/python-coverage-comment-action-data/htmlcov/index.html)

Using this one will allow you to [customize](https://shields.io/endpoint) the look of your badge.
It won't work with private repositories. It won't be refreshed more than once per five minutes.

### [Shields.io](https://shields.io) Dynamic Badge

[![Coverage badge](https://img.shields.io/badge/dynamic/json?color=brightgreen&label=coverage&query=%24.message&url=https%3A%2F%2Fraw.githubusercontent.com%2Fstinovlas%2Fprocrastinate%2Fpython-coverage-comment-action-data%2Fendpoint.json)](https://htmlpreview.github.io/?https://github.com/stinovlas/procrastinate/blob/python-coverage-comment-action-data/htmlcov/index.html)

This one will always be the same color. It won't work for private repos. I'm not even sure why we included it.

## What is that?

This branch is part of the
[python-coverage-comment-action](https://github.com/marketplace/actions/python-coverage-comment)
GitHub Action. All the files in this branch are automatically generated and may be
overwritten at any moment.