# The Hidden Language of Consumers: Decoding Unseen Patterns

## Project Overview

### Objective

The goal of this project is to conduct a comprehensive analysis of customer behavior and preferences. We aim to uncover patterns and insights that can inform business strategies and enhance customer engagement.

### Methodology

To achieve our objective, we will employ the following analytical methods:

* **Exploratory Data Analysis (EDA):** We will begin with EDA to understand the underlying structure of our data and to identify any interesting patterns or anomalies.
* **Univariate Analysis:** This will involve examining single variables to summarize and find patterns in the data.
* **Bivariate Analysis:** We will explore the relationship between two variables to understand the correlations and interactions between different customer attributes.
* **Unsupervised Learning Techniques:** We will use clustering algorithms to segment customers based on similar behaviors and preferences, which will help in targeting specific groups with tailored strategies.

### Expected Outcomes

By the end of this project, we anticipate the following outcomes:

* Identification of key customer segments.
* Insights into the preferences and behaviors of different customer groups.
* Recommendations for targeted marketing and product development strategies.

## Setup Locally

* Fork the repository

> Click the`Fork` button at the top right corner of this repository's page on GitHub. This will create a copy of the repository in your GitHub account.

* Clone this project

```bash
git clone https://github.com/OPCODE-Open-Spring-Fest/hidden-consumer-patterns   
```

* Enter project directory

```bash
cd hidden-consumer-patterns
```

* Install the nodeJS dependecies

```bash
npm i
```

* Create a new branch for your feature or bug fix.

* Make your changes and commit them.

* Push to the branch.

* Submit a pull request.

## Repository structure

```text

├───.github
│   ├───Contributor_Guide
│   ├───ISSUE_TEMPLATE
│   ├───PULL_REQUEST_TEMPLATE
│   └───workflows
├───.husky
│   └───_
├───dataset
└───node_modules
    ├───.bin
    ├───@babel
    │   ├───code-frame
    │   │   ├───lib
    │   │   └───node_modules
    │   │       ├───ansi-styles
    │   │       ├───chalk
    │   │       │   └───types
    │   │       ├───color-convert
    │   │       └───color-name
    │   ├───helper-validator-identifier
    │   │   ├───lib
    │   │   └───scripts
    │   └───highlight
    │       ├───lib
    │       └───node_modules
    │           ├───ansi-styles
    │           ├───chalk
    │           │   └───types
    │           ├───color-convert
    │           └───color-name
    ├───@commitlint
    │   ├───cli
    │   │   └───lib
    │   ├───config-conventional
    │   │   └───lib
    │   ├───config-validator
    │   │   └───lib
    │   ├───ensure
    │   │   └───lib
    │   ├───execute-rule
    │   │   └───lib
    │   ├───format
    │   │   └───lib
    │   ├───is-ignored
    │   │   └───lib
    │   ├───lint
    │   │   └───lib
    │   ├───load
    │   │   └───lib
    │   │       └───utils
    │   ├───message
    │   │   └───lib
    │   ├───parse
    │   │   └───lib
    │   ├───read
    │   │   └───lib
    │   ├───resolve-extends
    │   │   └───lib
    │   ├───rules
    │   │   └───lib
    │   ├───to-lines
    │   │   └───lib
    │   ├───top-level
    │   │   └───lib
    │   └───types
    │       └───lib
    ├───@types
    │   ├───conventional-commits-parser
    │   │   └───ts4.9
    │   └───node
    │       ├───assert
    │       ├───dns
    │       ├───fs
    │       ├───readline
    │       ├───stream
    │       └───timers
    ├───ajv
    │   ├───dist
    │   │   ├───compile
    │   │   │   ├───codegen
    │   │   │   ├───jtd
    │   │   │   └───validate
    │   │   ├───refs
    │   │   │   ├───json-schema-2019-09
    │   │   │   │   └───meta
    │   │   │   └───json-schema-2020-12
    │   │   │       └───meta
    │   │   ├───runtime
    │   │   ├───standalone
    │   │   ├───types
    │   │   └───vocabularies
    │   │       ├───applicator
    │   │       ├───core
    │   │       ├───discriminator
    │   │       ├───dynamic
    │   │       ├───format
    │   │       ├───jtd
    │   │       ├───unevaluated
    │   │       └───validation
    │   └───lib
    │       ├───compile
    │       │   ├───codegen
    │       │   ├───jtd
    │       │   └───validate
    │       ├───refs
    │       │   ├───json-schema-2019-09
    │       │   │   └───meta
    │       │   └───json-schema-2020-12
    │       │       └───meta
    │       ├───runtime
    │       ├───standalone
    │       ├───types
    │       └───vocabularies
    │           ├───applicator
    │           ├───core
    │           ├───discriminator
    │           ├───dynamic
    │           ├───format
    │           ├───jtd
    │           ├───unevaluated
    │           └───validation
    ├───ansi-regex
    ├───ansi-styles
    ├───argparse
    │   └───lib
    ├───array-ify
    ├───callsites
    ├───chalk
    │   └───source
    │       └───vendor
    │           ├───ansi-styles
    │           └───supports-color
    ├───cliui
    │   └───build
    │       └───lib
    ├───color-convert
    ├───color-name
    ├───compare-func
    ├───conventional-changelog-angular
    │   └───templates
    ├───conventional-changelog-conventionalcommits
    │   └───templates
    ├───conventional-commits-parser
    │   └───lib
    ├───cosmiconfig
    │   └───dist
    ├───cosmiconfig-typescript-loader
    │   └───dist
    │       ├───cjs
    │       ├───esm
    │       └───types
    ├───cross-spawn
    │   └───lib
    │       └───util
    ├───dargs
    ├───dot-prop
    ├───emoji-regex
    │   └───es2015
    ├───error-ex
    ├───escalade
    │   ├───dist
    │   └───sync
    ├───escape-string-regexp
    ├───execa
    │   └───lib
    ├───fast-deep-equal
    │   └───es6
    ├───find-up
    ├───get-caller-file
    ├───get-stream
    │   └───source
    ├───git-raw-commits
    ├───global-directory
    ├───has-flag
    ├───human-signals
    │   └───build
    │       └───src
    ├───husky
    ├───import-fresh
    │   └───node_modules
    │       └───resolve-from
    ├───import-meta-resolve
    │   └───lib
    ├───ini
    │   └───lib
    ├───is-arrayish
    ├───is-fullwidth-code-point
    ├───is-obj
    ├───is-stream
    ├───is-text-path
    ├───isexe
    │   └───test
    ├───jiti
    │   ├───bin
    │   ├───dist
    │   │   └───plugins
    │   └───lib
    ├───js-tokens
    ├───js-yaml
    │   ├───bin
    │   ├───dist
    │   └───lib
    │       ├───schema
    │       └───type
    ├───json-parse-even-better-errors
    ├───json-schema-traverse
    │   ├───.github
    │   │   └───workflows
    │   └───spec
    │       └───fixtures
    ├───jsonparse
    │   ├───examples
    │   ├───samplejson
    │   └───test
    ├───JSONStream
    │   ├───examples
    │   └───test
    │       └───fixtures
    ├───lines-and-columns
    │   └───build
    ├───locate-path
    ├───lodash.camelcase
    ├───lodash.isplainobject
    ├───lodash.kebabcase
    ├───lodash.merge
    ├───lodash.mergewith
    ├───lodash.snakecase
    ├───lodash.startcase
    ├───lodash.uniq
    ├───lodash.upperfirst
    ├───lru-cache
    ├───meow
    │   └───build
    ├───merge-stream
    ├───mimic-fn
    ├───minimist
    │   ├───.github
    │   ├───example
    │   └───test
    ├───npm-run-path
    │   └───node_modules
    │       └───path-key
    ├───onetime
    ├───p-limit
    ├───p-locate
    ├───parent-module
    ├───parse-json
    ├───path-exists
    ├───path-key
    ├───path-type
    ├───punycode
    ├───require-directory
    ├───require-from-string
    ├───resolve-from
    ├───semver
    │   ├───bin
    │   ├───classes
    │   ├───functions
    │   ├───internal
    │   └───ranges
    ├───shebang-command
    ├───shebang-regex
    ├───signal-exit
    │   └───dist
    │       ├───cjs
    │       └───mjs
    ├───split2
    ├───string-width
    ├───strip-ansi
    ├───strip-final-newline
    ├───supports-color
    ├───text-extensions
    ├───through
    │   └───test
    ├───typescript
    │   ├───bin
    │   └───lib
    │       ├───cs
    │       ├───de
    │       ├───es
    │       ├───fr
    │       ├───it
    │       ├───ja
    │       ├───ko
    │       ├───pl
    │       ├───pt-br
    │       ├───ru
    │       ├───tr
    │       ├───zh-cn
    │       └───zh-tw
    ├───undici-types
    ├───unicorn-magic
    ├───uri-js
    │   └───dist
    │       ├───es5
    │       └───esnext
    │           └───schemes
    ├───which
    │   └───bin
    ├───wrap-ansi
    ├───y18n
    │   └───build
    │       └───lib
    │           └───platform-shims
    ├───yallist
    ├───yargs
    │   ├───build
    │   │   └───lib
    │   │       ├───typings
    │   │       └───utils
    │   ├───helpers
    │   ├───lib
    │   │   └───platform-shims
    │   └───locales
    ├───yargs-parser
    │   └───build
    │       └───lib
    └───yocto-queue
    
```
