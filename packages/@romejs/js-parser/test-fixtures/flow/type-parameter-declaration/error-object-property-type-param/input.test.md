# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > type-parameter-declaration > error-object-property-type-param`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 21
      line: 4
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
        advice: Array []
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Unexpected token'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 1
          index: 20
          line: 3
        }
        start: Object {
          column: 0
          index: 19
          line: 3
        }
      }
    }
  ]
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 1
          index: 20
          line: 3
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'const'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 1
            index: 20
            line: 3
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingIdentifier {
              name: 's'
              loc: Object {
                filename: 'input.js'
                identifierName: 's'
                end: Object {
                  column: 7
                  index: 7
                  line: 1
                }
                start: Object {
                  column: 6
                  index: 6
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 1
                index: 20
                line: 3
              }
              start: Object {
                column: 6
                index: 6
                line: 1
              }
            }
            init: ObjectExpression {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 1
                  index: 20
                  line: 3
                }
                start: Object {
                  column: 10
                  index: 10
                  line: 1
                }
              }
              properties: Array [
                ObjectProperty {
                  key: StaticPropertyKey {
                    value: Identifier {
                      name: 'p'
                      loc: Object {
                        filename: 'input.js'
                        identifierName: 'p'
                        end: Object {
                          column: 3
                          index: 15
                          line: 2
                        }
                        start: Object {
                          column: 2
                          index: 14
                          line: 2
                        }
                      }
                    }
                    variance: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 3
                        index: 15
                        line: 2
                      }
                      start: Object {
                        column: 2
                        index: 14
                        line: 2
                      }
                    }
                  }
                  value: ReferenceIdentifier {
                    name: 'p'
                    loc: Object {
                      filename: 'input.js'
                      identifierName: 'p'
                      end: Object {
                        column: 3
                        index: 15
                        line: 2
                      }
                      start: Object {
                        column: 2
                        index: 14
                        line: 2
                      }
                    }
                  }
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 6
                      index: 18
                      line: 2
                    }
                    start: Object {
                      column: 2
                      index: 14
                      line: 2
                    }
                  }
                }
              ]
            }
          }
        ]
      }
    }
  ]
}
```
