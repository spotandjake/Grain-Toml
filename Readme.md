# Grain-Toml
This repo contains a very basic toml parser written in grain-lang.

# To Be Done
This library is by no means completes
## Tests
+ [ ] Parsing
  + [ ] Expressions
    + [ ] Parse Comments
      + [x] Parsing Comments
      + [ ] Allow comments to be parsed at the end of a line
    + [x] Parse Key Values
    + [x] Parse Tables
    + [ ] Parse Array Tables
    + [ ] Parse keys such as `a.b` in Table headers and Key Value Pairs
    + [ ] Ensure keys are valid
    + [ ] Properly Parse String Keys
    + [ ] Properly handle empty string keys
    + [ ] Verify things are on newlines
  + [ ] Toml Values
    + [x] Booleans
    + [ ] Strings
      + [ ] Basic Strings
        + [x] Parsing
        + [ ] Normalizing
      + [ ] Basic Multiline Strings
        + [x] Parsing
        + [ ] Trimming
      + [ ] Literal Strings
        + [ ] Parsing
        + [ ] Research Normalization or trimming
      + [ ] Literal Multiline Strings
        + [ ] Parsing
        + [ ] Research Normalization or trimming
    + [ ] Integers
      + [ ] Parsing
    + [ ] Floats
      + [ ] Parsing
    + [ ] Arrays
      + [ ] Parsing
    + [ ] Inline Tables
      + [ ] Parsing
    + [ ] Date's
      + [ ] Parsing
      + [ ] Determine how we want to represent these
  + [ ] Add Option For A Searchable Api
+ [ ] Stringify
+ [ ] Testing
  + [ ] Parsing
    + [ ] Run The Toml Verification Tests through to ensure full coverage and compliance with the spec.
+ [ ] Refactor
  + [ ] After everything else is done we need to go back through and refactor the entire library for performance and readability.
