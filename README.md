# Olivierpironneau FreeFem

freefem.org has a .dmg which installs freefem, with one advantage: you can double click FreeFEM.app in the "Applications" folder.  If you think you will use freefem only via the terminal or VS Code or TextMate, then use homebrew to install freefem.

## How do I install these formulae?

```ruby
brew tap olivierpironneau/freefem
brew install freefem
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).

Note that PETSC and MPI is part of this formula.  

Note also that this formula does not install a freefem.aapp in the application folder.  It could be done by typing 'freefem-install-app' after the brew install, but this app does not open a choose-file dialog, so it's pretty useless (we are working on it).
