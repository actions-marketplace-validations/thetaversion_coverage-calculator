# Coverage score calculate

Calculates coverage score base on lcov.info file.

## Inputs

## `lcov-file`

**Optional** The lcov.info file location. Default `"./coverage/lcov.info"`.

## Outputs

## `score`

The score of the calculation result.

## Example usage

    uses: thetaversion/coverage-calculator@{VERSION}
    with:
        lcov-file: './coverage/lcov.info'

## LICENSE

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
