# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > async-functions > invalid-escape-async-class-method`

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
      index: 39
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'async can\'t contain a unicode escape'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 10
          index: 10
          line: 1
        }
        start: Object {
          column: 10
          index: 10
          line: 1
        }
      }
    }
  ]
  body: Array [
    ClassDeclaration {
      id: BindingIdentifier {
        name: 'X'
        loc: Object {
          filename: 'input.js'
          identifierName: 'X'
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
          column: 38
          index: 38
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      meta: ClassHead {
        implements: undefined
        superClass: undefined
        superTypeParameters: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 38
            index: 38
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        body: Array [
          ClassMethod {
            kind: 'method'
            key: StaticPropertyKey {
              value: Identifier {
                name: 'x'
                loc: Object {
                  filename: 'input.js'
                  identifierName: 'x'
                  end: Object {
                    column: 22
                    index: 22
                    line: 1
                  }
                  start: Object {
                    column: 21
                    index: 21
                    line: 1
                  }
                }
              }
              variance: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 22
                  index: 22
                  line: 1
                }
                start: Object {
                  column: 21
                  index: 21
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 36
                index: 36
                line: 1
              }
              start: Object {
                column: 10
                index: 10
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
                  column: 24
                  index: 24
                  line: 1
                }
                start: Object {
                  column: 22
                  index: 22
                  line: 1
                }
              }
            }
            meta: ClassPropertyMeta {
              abstract: false
              accessibility: undefined
              optional: false
              readonly: false
              static: false
              typeAnnotation: undefined
              start: Object {
                column: 10
                index: 10
                line: 1
              }
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 22
                  index: 22
                  line: 1
                }
                start: Object {
                  column: 10
                  index: 10
                  line: 1
                }
              }
            }
            body: BlockStatement {
              directives: Array []
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 36
                  index: 36
                  line: 1
                }
                start: Object {
                  column: 25
                  index: 25
                  line: 1
                }
              }
              body: Array [
                ExpressionStatement {
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 34
                      index: 34
                      line: 1
                    }
                    start: Object {
                      column: 27
                      index: 27
                      line: 1
                    }
                  }
                  expression: AwaitExpression {
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 34
                        index: 34
                        line: 1
                      }
                      start: Object {
                        column: 27
                        index: 27
                        line: 1
                      }
                    }
                    argument: ReferenceIdentifier {
                      name: 'x'
                      loc: Object {
                        filename: 'input.js'
                        identifierName: 'x'
                        end: Object {
                          column: 34
                          index: 34
                          line: 1
                        }
                        start: Object {
                          column: 33
                          index: 33
                          line: 1
                        }
                      }
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
