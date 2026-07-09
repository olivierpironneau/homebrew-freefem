# Olivierpironneau Freefem

## How do I install these formulae?

```ruby
brew tap "olivierpironneau/freefem"
brew "freefem"
```
Or

`brew install olivierpironneau/freefem/freefem`

Or `brew tap olivierpironneau/freefem` and then `brew install freefem`.

Or, in a `brew bundle` `Brewfile`:



## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).

Note that PETSC is not part of this formula.  For PETSC you have to compite freefem from the source.

Note also that this formula does not install a freefem.aapp in the application folder.  It could be done by typing 'freefem-install-app' after the brew install, but this app does not open a choose-file dialog, so it's pretty useless (we are working on it).
