
<a name="v0.1.5"></a>
## [v0.1.5](https://github.com/dmlittle/scenery/compare/v0.1.4...v0.1.5) (2019-04-17)

### Bug Fixes

* **number:** fix printing float precision ([#29](https://github.com/dmlittle/scenery/issues/29))
* **print:** remove infinite recursion in formatValue fn ([#27](https://github.com/dmlittle/scenery/issues/27))

### Features

* **base64:** decode base64 simple output if possible ([#25](https://github.com/dmlittle/scenery/issues/25))


<a name="v0.1.4"></a>
## [v0.1.4](https://github.com/dmlittle/scenery/compare/v0.1.3...v0.1.4) (2019-03-28)

### Bug Fixes

* **parsing:** enable lookahead of 3 ([#23](https://github.com/dmlittle/scenery/issues/23))

### Chore

* **cleanup:** remove empty test file


<a name="v0.1.3"></a>
## [v0.1.3](https://github.com/dmlittle/scenery/compare/v0.1.2...v0.1.3) (2019-03-25)

### Bug Fixes

* **parser:** allow alphanumeric header values ([#21](https://github.com/dmlittle/scenery/issues/21))
* **print:** remove bug with trimming trailing new line in multi line text ([#19](https://github.com/dmlittle/scenery/issues/19))

### Chore

* **test:** fix multiline printer test
* **test:** add hyphen test ([#20](https://github.com/dmlittle/scenery/issues/20))

### Features

* **diff:** add diff for base64 values ([#16](https://github.com/dmlittle/scenery/issues/16))


<a name="v0.1.2"></a>
## [v0.1.2](https://github.com/dmlittle/scenery/compare/v0.1.1...v0.1.2) (2019-02-22)

### Bug Fixes

* **parser:** allow hyphen in attribute keys ([#15](https://github.com/dmlittle/scenery/issues/15))
* **parser:** allow slash symbols in attribute keys ([#14](https://github.com/dmlittle/scenery/issues/14))


<a name="v0.1.1"></a>
## [v0.1.1](https://github.com/dmlittle/scenery/compare/v0.1.0...v0.1.1) (2019-01-20)

### Bug Fixes

* **diff:** json.Marshal JSON diff to ensure formatting is equal ([#9](https://github.com/dmlittle/scenery/issues/9))
* **parser:** recover from parser panics and return original input ([#7](https://github.com/dmlittle/scenery/issues/7))
* **version:** set default version to 'dev' ([#2](https://github.com/dmlittle/scenery/issues/2))

### Chore

* **demo:** add demo recording to README ([#3](https://github.com/dmlittle/scenery/issues/3))

### Features

* **diff:** also show JSON diff output with arrays
* **printer:** skip complex attributes where value did not change


<a name="v0.1.0"></a>
## v0.1.0 (2019-01-12)

### Chore

* **circle-ci:** add CircleCI integration ([#1](https://github.com/dmlittle/scenery/issues/1))
* **repo:** initial repo commit

### Features

* **scenery:** initial public version of scenery

