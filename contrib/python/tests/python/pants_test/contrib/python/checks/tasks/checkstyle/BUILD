# Copyright 2015 Pants project contributors (see CONTRIBUTORS.md).
# Licensed under the Apache License, Version 2.0 (see LICENSE).

python_tests(
  sources=globs('*.py'),
  dependencies=[
    'contrib/python/src/python/pants/contrib/python/checks/tasks/checkstyle:all',
    'src/python/pants/util:dirutil',
    'tests/python/pants_test/backend/python/tasks:python_task_test_base',
    'tests/python/pants_test/option/util',
    'tests/python/pants_test:base_test',
  ]
)
