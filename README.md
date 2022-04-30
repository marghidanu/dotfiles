# dotfiles

## Setup

Before you begin, you will need to install `brew` onto your system. Run the following command to install it:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Follow the steps at the end to finalize your installation. Now we can install the rest of the applications:

```
brew bundle -v
```

Once everything is in place,  let's configure the system:

```
werk run
```

## References

* [Homebrew](https://brew.sh)
* [Homebrew bundles](https://github.com/Homebrew/homebrew-bundle)
* [Werk](https://github.com/marghidanu/werk)