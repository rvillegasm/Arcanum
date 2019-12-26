# Arcanum
Default software repository for the **`Sage`** package manager.

## Repository structure

Every software package is called `Tome` inside **`Arcanum`**. Every `Tome` has it's own directory inside `Arcanum`'s root directory, and inside every `Tome`'s directory you will find:

- A *metadata.yml* file containing information about the `Tome`, like the amount of versions of said `Tome` that are available for download, what the latest version and the *LTS* version of said `Tome` is, and more.

- Several *\<Tome-name>_\<Tome-version>.yml* files, each containing the *name* of the package, it's *version*, the *url* from where it will be downloaded the *type* of file that will be downloaded (e.g. zip, tar, etc.), and the name of the file to be downloaded.

**Note:** Arcanum is still in early development, so we are still thinking about what the *metadata* for every `Tome` should be. If you have any suggestions, please be sure to raise an issue over on github and tell us about it.

## Contributing

**Contributions are always welcome!** If you want to contribute, please fork us, create a new feature branch, add the new `Tome` and/or *file* that you want added to the repository, and submit a pull request. We will analyze it and add it to `Arcanum` as quickly as we possibly can.
