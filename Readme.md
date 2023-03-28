# Grain-Toml
This repo contains a very basic toml parser written in grain-lang.

Feel free to use this in your project or as inspiration for a better toml-parser.

# To Be Done
This library is by no means completes, Some Notable Things Missings Are
+ Array Tables
+ Date Support
+ Validation
  + Validate Keys Only Occur Once
  
## Completed
+ [ ] Parsing
  + [ ] Array tables
  + [x] Tables
  + [ ] Expressions
    + [x] Parse Comments
      + [x] Parsing Comments
      + [x] Allow comments to be parsed at the end of a line
      + [x] Research allowing comments inside of arrays and tables
    + [x] Parse Key Values
    + [x] Parse Tables
    + [x] Parse Array Tables
    + [x] Parse keys such as `a.b` in Table headers and Key Value Pairs
    + [x] Ensure keys are valid
    + [x] Properly Parse String Keys
    + [x] Properly handle empty string keys
    + [ ] Verify things are on newlines
  + [ ] Toml Values
    + [x] Booleans
    + [x] Strings
      + [x] Basic Strings
        + [x] Parsing
        + [x] Normalizing
      + [x] Basic Multiline Strings
        + [x] Parsing
        + [x] Trimming
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
