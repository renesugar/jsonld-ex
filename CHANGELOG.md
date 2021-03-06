# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/) and
[Keep a CHANGELOG](http://keepachangelog.com).


## 0.2.2 - 2018-03-17

### Added

- JSON-LD encoder can handle `RDF.Graph`s and `RDF.Description`s 

### Changed

- Use Jason instead of Poison for JSON encoding and decoding, since it's faster and more standard conform


[Compare v0.2.1...v0.2.2](https://github.com/marcelotto/jsonld-ex/compare/v0.2.1...v0.2.2)



## 0.2.1 - 2018-03-10

### Changed

- Upgrade to RDF.ex 0.4.0
- Fixed all warnings ([@talklittle](https://github.com/talklittle)) 


[Compare v0.2.0...v0.2.1](https://github.com/marcelotto/jsonld-ex/compare/v0.2.0...v0.2.1)



## 0.2.0 - 2017-08-24

### Changed

- Upgrade to RDF.ex 0.3.0


[Compare v0.1.1...v0.2.0](https://github.com/marcelotto/jsonld-ex/compare/v0.1.1...v0.2.0)



## 0.1.1 - 2017-08-06

### Changed

- Don't support Elixir versions < 1.5, since `URI.merge` is broken in earlier versions  


[Compare v0.1.0...v0.1.1](https://github.com/marcelotto/jsonld-ex/compare/v0.1.0...v0.1.1)



## 0.1.0 - 2017-06-25

Initial release
