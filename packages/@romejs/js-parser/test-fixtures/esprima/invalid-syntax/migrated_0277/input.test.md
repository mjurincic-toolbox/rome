# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0277`

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
      index: 20
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'enum is a reserved word'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 15
          index: 15
          line: 1
        }
        start: Object {
          column: 11
          index: 11
          line: 1
        }
      }
    }
  ]
  body: Array [
    ClassDeclaration {
      id: BindingIdentifier {
        name: 'A'
        loc: Object {
          filename: 'input.js'
          identifierName: 'A'
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
          column: 19
          index: 19
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
            column: 19
            index: 19
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
                name: 'a'
                loc: Object {
                  filename: 'input.js'
                  identifierName: 'a'
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
              variance: undefined
              loc: Object {
                filename: 'input.js'
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
                column: 18
                index: 18
                line: 1
              }
              start: Object {
                column: 9
                index: 9
                line: 1
              }
            }
            body: BlockStatement {
              body: Array []
              directives: Array []
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 18
                  index: 18
                  line: 1
                }
                start: Object {
                  column: 16
                  index: 16
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
                column: 9
                index: 9
                line: 1
              }
              loc: Object {
                filename: 'input.js'
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
            head: FunctionHead {
              async: false
              generator: false
              hasHoistedVars: false
              predicate: undefined
              rest: undefined
              returnType: undefined
              thisType: undefined
              typeParameters: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 16
                  index: 16
                  line: 1
                }
                start: Object {
                  column: 10
                  index: 10
                  line: 1
                }
              }
              params: Array [
                BindingIdentifier {
                  name: 'enum'
                  loc: Object {
                    filename: 'input.js'
                    identifierName: 'enum'
                    end: Object {
                      column: 15
                      index: 15
                      line: 1
                    }
                    start: Object {
                      column: 11
                      index: 11
                      line: 1
                    }
                  }
                  meta: PatternMeta {
                    optional: undefined
                    typeAnnotation: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 15
                        index: 15
                        line: 1
                      }
                      start: Object {
                        column: 11
                        index: 11
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
    }
  ]
}
```
