# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 69`

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
      column: 16
      index: 16
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 16
          index: 16
          line: 1
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
            column: 16
            index: 16
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingObjectPattern {
              rest: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 11
                  index: 11
                  line: 1
                }
                start: Object {
                  column: 6
                  index: 6
                  line: 1
                }
              }
              properties: Array [
                BindingObjectPatternProperty {
                  key: StaticPropertyKey {
                    value: Identifier {
                      name: 'a'
                      loc: Object {
                        filename: 'input.js'
                        identifierName: 'a'
                        end: Object {
                          column: 8
                          index: 8
                          line: 1
                        }
                        start: Object {
                          column: 7
                          index: 7
                          line: 1
                        }
                      }
                    }
                    variance: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 8
                        index: 8
                        line: 1
                      }
                      start: Object {
                        column: 7
                        index: 7
                        line: 1
                      }
                    }
                  }
                  value: BindingIdentifier {
                    name: 'b'
                    loc: Object {
                      filename: 'input.js'
                      identifierName: 'b'
                      end: Object {
                        column: 10
                        index: 10
                        line: 1
                      }
                      start: Object {
                        column: 9
                        index: 9
                        line: 1
                      }
                    }
                  }
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 10
                      index: 10
                      line: 1
                    }
                    start: Object {
                      column: 7
                      index: 7
                      line: 1
                    }
                  }
                }
              ]
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 16
                index: 16
                line: 1
              }
              start: Object {
                column: 6
                index: 6
                line: 1
              }
            }
            init: ObjectExpression {
              properties: Array []
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 16
                  index: 16
                  line: 1
                }
                start: Object {
                  column: 14
                  index: 14
                  line: 1
                }
              }
            }
          }
        ]
      }
    }
  ]
}
```
