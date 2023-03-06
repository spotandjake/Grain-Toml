# Grain-Toml
This repo contains a very basic toml parser written in grain-lang.

# To Be Done
This library is by no means completes
## Tests
+ [ ] Parsing
  + [ ] Expressions
    + [x] Parse Comments
      + [x] Parsing Comments
      + [x] Allow comments to be parsed at the end of a line
      + [x] Research allowing comments inside of arrays and tables
    + [x] Parse Key Values
    + [x] Parse Tables
    + [x] Parse Array Tables
    + [x] Parse keys such as `a.b` in Table headers and Key Value Pairs
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
      + [x] Literal Strings
        + [x] Parsing
      + [x] Literal Multiline Strings
        + [x] Parsing
    + [x] Integers
      + [x] Parsing
    + [x] Floats
      + [x] Parsing
    + [x] Arrays
      + [x] Parsing
    + [x] Inline Tables
      + [x] Parsing
    + [ ] Date's
      + [ ] Parsing
      + [ ] Determine how we want to represent these
  + [ ] Add Option For A Searchable Api
+ [ ] Stringify
+ [ ] Testing
  + [ ] Parsing
    + [ ] Run The Toml Verification Tests through to ensure full coverage and compliance with the spec.
