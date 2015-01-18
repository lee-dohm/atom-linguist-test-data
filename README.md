# Atom Linguist Test Data

This is a repository of files to use to test the accuracy of [Atom Linguist's][atom-linguist] file type classification. The goal, of course, is that Atom Linguist should always be able to classify the contents of this repository with 100% accuracy as measured by the system in [this blog post][accuracy].

## Structure

The repository contains directories with names that match a single language entry from the Atom Linguist [languages file][languages]. Inside each directory is one or more example files that should be detected as the language specified in the directory name. For example:

* `CoffeeScript/file-blob.coffee` should be detected as `CoffeeScript`
* `YAML/languages.yml` should be detected as `YAML`

The directory name *must* match identically and case-sensitively to the name of the language in the official language list.

## Contributing

See the [CONTRIBUTING][contributing] document.

## Copyright

Copyright &copy; 2015 by [Lee Dohm](http://www.lee-dohm.com). See [LICENSE][license] for details.

[accuracy]: http://www.lee-dohm.com/2015/01/11/linguist-for-atom-evaluating-accuracy.html
[atom-linguist]: https://github.com/lee-dohm/atom-linguist
[contributing]: https://github.com/lee-dohm/atom-linguist-test-data/blob/master/CONTRIBUTING.md
[languages]: https://github.com/lee-dohm/atom-linguist/blob/master/data/languages.yml
[license]: https://github.com/lee-dohm/atom-linguist-test-data/blob/master/LICENSE.md
