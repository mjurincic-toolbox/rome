# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > async-functions > invalid-escape-await`

```javascript
Program {
  comments: Array []
  corrupt: false
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
      index: 36
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Can not use \'await\' as identifier inside an async function'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 30
          index: 30
          line: 1
        }
        start: Object {
          column: 20
          index: 20
          line: 1
        }
      }
    }
  ]
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 35
          index: 35
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: FunctionExpression {
        id: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 34
            index: 34
            line: 1
          }
          start: Object {
            column: 1
            index: 1
            line: 1
          }
        }
        head: FunctionHead {
          async: true
          generator: false
          hasHoistedVars: false
          params: Array []
          predicate: undefined
          rest: undefined
          returnType: undefined
          thisType: undefined
          typeParameters: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 17
              index: 17
              line: 1
            }
            start: Object {
              column: 15
              index: 15
              line: 1
            }
          }
        }
        body: BlockStatement {
          directives: Array []
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 34
              index: 34
              line: 1
            }
            start: Object {
              column: 18
              index: 18
              line: 1
            }
          }
          body: Array [
            ExpressionStatement {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 30
                  index: 30
                  line: 1
                }
                start: Object {
                  column: 20
                  index: 20
                  line: 1
                }
              }
              expression: ReferenceIdentifier {
                name: 'await'
                loc: Object {
                  filename: 'input.js'
                  identifierName: 'await'
                  end: Object {
                    column: 30
                    index: 30
                    line: 1
                  }
                  start: Object {
                    column: 20
                    index: 20
                    line: 1
                  }
                }
              }
            }
            ExpressionStatement {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 32
                  index: 32
                  line: 1
                }
                start: Object {
                  column: 31
                  index: 31
                  line: 1
                }
              }
              expression: ReferenceIdentifier {
                name: 'x'
                loc: Object {
                  filename: 'input.js'
                  identifierName: 'x'
                  end: Object {
                    column: 32
                    index: 32
                    line: 1
                  }
                  start: Object {
                    column: 31
                    index: 31
                    line: 1
                  }
                }
              }
            }
          ]
        }
      }
    }
  ]
}
```
