# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 542`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 18
      line: 3
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 11
          index: 17
          line: 2
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: CallExpression {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 11
            index: 17
            line: 2
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        arguments: Array [
          StringLiteral {
            value: ' '
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 10
                index: 16
                line: 2
              }
              start: Object {
                column: 7
                index: 13
                line: 2
              }
            }
          }
        ]
        callee: MemberExpression {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 6
              index: 12
              line: 2
            }
            start: Object {
              column: 0
              index: 0
              line: 1
            }
          }
          object: StringLiteral {
            value: 'foo'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 5
                index: 5
                line: 1
              }
              start: Object {
                column: 0
                index: 0
                line: 1
              }
            }
          }
          property: StaticMemberProperty {
            value: Identifier {
              name: 'split'
              loc: Object {
                filename: 'input.js'
                identifierName: 'split'
                end: Object {
                  column: 6
                  index: 12
                  line: 2
                }
                start: Object {
                  column: 1
                  index: 7
                  line: 2
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              identifierName: 'split'
              end: Object {
                column: 6
                index: 12
                line: 2
              }
              start: Object {
                column: 1
                index: 7
                line: 2
              }
            }
          }
        }
      }
    }
  ]
}
```
