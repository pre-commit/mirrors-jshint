jshint mirror
================

Mirror of jshint package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit
For jshint: see https://github.com/jshint/jshint


### Using jshint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/pre-commit/mirrors-jshint
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: jshint
