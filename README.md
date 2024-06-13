copies the ansible-core `copy` module, but fixes a bug where diffs are discarded with multiple files.

If [this pull request](https://github.com/ansible/ansible/pull/81346) is merged, we can abandon this collection and use ansible-core.
