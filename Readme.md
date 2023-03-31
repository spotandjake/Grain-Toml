# Grain-Toml
This repo contains a mostly complete toml parser for the grain language. The parser supports the toml `v1.1.0` spec which has not been released yet and is still in motion but it is mostly backwards compatible with the `v1.0.0` spec and should be able to parse most toml files. 

Feel free to use this in your project or as inspiration for a better toml-parser.

# To Be Done
This library is by no means completes, Some Notable Things Missing Are
+ Fix Key Duplication Detection
+ Date Support
  + Consider representing date's as numbers until grain has actual date support
  + Validate Seconds Against Leap Seconds
  + Allow Optional Seconds
+ Validation
  + Fix Key Duplicate Validation