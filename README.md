# OdinsPlasmaRifle

## Usage

### Download/Clone

When cloning the repository ensure you do so recursively:

```sh
git clone --recurse-submodules git@github.com:odinsplasmarifle/odinsplasmarifle.git
```

When pulling new changes from `main` make sure you also run the following afterwards to get the latest submodule updates.

```sh
git submodule update
```

If a submodule has been updated at its origin, then you will need to merge these updates into the repository using:

```sh
git submodule update --remote --merge
```

And then commit/push the new submodule.

### Development

Ensure you have Hugo version `0.78.1 (extended)` installed and then run:

```sh
hugo serve
```
