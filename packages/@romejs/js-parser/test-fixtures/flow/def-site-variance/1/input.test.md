# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > def-site-variance > 1`

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
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 60
      line: 4
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ClassDeclaration {
      id: BindingIdentifier {
        name: 'C'
        loc: Object {
          filename: 'input.js'
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
          column: 17
          index: 17
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      meta: ClassHead {
        body: Array []
        implements: undefined
        superClass: undefined
        superTypeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 17
            index: 17
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        typeParameters: FlowTypeParameterDeclaration {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 14
              index: 14
              line: 1
            }
            start: Object {
              column: 7
              index: 7
              line: 1
            }
          }
          params: Array [
            FlowTypeParameter {
              name: 'T'
              bound: undefined
              default: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 10
                  index: 10
                  line: 1
                }
                start: Object {
                  column: 8
                  index: 8
                  line: 1
                }
              }
              variance: FlowVariance {
                kind: 'plus'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 9
                    index: 9
                    line: 1
                  }
                  start: Object {
                    column: 8
                    index: 8
                    line: 1
                  }
                }
              }
            }
            FlowTypeParameter {
              name: 'U'
              bound: undefined
              default: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 13
                  index: 13
                  line: 1
                }
                start: Object {
                  column: 11
                  index: 11
                  line: 1
                }
              }
              variance: FlowVariance {
                kind: 'minus'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 12
                    index: 12
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
    }
    FunctionDeclaration {
      id: BindingIdentifier {
        name: 'f'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 10
            index: 28
            line: 2
          }
          start: Object {
            column: 9
            index: 27
            line: 2
          }
        }
      }
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 22
          index: 40
          line: 2
        }
        start: Object {
          column: 0
          index: 18
          line: 2
        }
      }
      body: BlockStatement {
        body: Array []
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 22
            index: 40
            line: 2
          }
          start: Object {
            column: 20
            index: 38
            line: 2
          }
        }
      }
      head: FunctionHead {
        async: false
        generator: false
        hasHoistedVars: false
        params: Array []
        predicate: undefined
        rest: undefined
        returnType: undefined
        thisType: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 20
            index: 38
            line: 2
          }
          start: Object {
            column: 10
            index: 28
            line: 2
          }
        }
        typeParameters: FlowTypeParameterDeclaration {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 17
              index: 35
              line: 2
            }
            start: Object {
              column: 10
              index: 28
              line: 2
            }
          }
          params: Array [
            FlowTypeParameter {
              name: 'T'
              bound: undefined
              default: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 13
                  index: 31
                  line: 2
                }
                start: Object {
                  column: 11
                  index: 29
                  line: 2
                }
              }
              variance: FlowVariance {
                kind: 'plus'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 12
                    index: 30
                    line: 2
                  }
                  start: Object {
                    column: 11
                    index: 29
                    line: 2
                  }
                }
              }
            }
            FlowTypeParameter {
              name: 'U'
              bound: undefined
              default: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 16
                  index: 34
                  line: 2
                }
                start: Object {
                  column: 14
                  index: 32
                  line: 2
                }
              }
              variance: FlowVariance {
                kind: 'minus'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 15
                    index: 33
                    line: 2
                  }
                  start: Object {
                    column: 14
                    index: 32
                    line: 2
                  }
                }
              }
            }
          ]
        }
      }
    }
    TypeAliasTypeAnnotation {
      id: BindingIdentifier {
        name: 'T'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 6
            index: 47
            line: 3
          }
          start: Object {
            column: 5
            index: 46
            line: 3
          }
        }
      }
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 18
          index: 59
          line: 3
        }
        start: Object {
          column: 0
          index: 41
          line: 3
        }
      }
      right: FlowObjectTypeAnnotation {
        exact: false
        inexact: undefined
        properties: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 18
            index: 59
            line: 3
          }
          start: Object {
            column: 16
            index: 57
            line: 3
          }
        }
      }
      typeParameters: FlowTypeParameterDeclaration {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 13
            index: 54
            line: 3
          }
          start: Object {
            column: 6
            index: 47
            line: 3
          }
        }
        params: Array [
          FlowTypeParameter {
            name: 'T'
            bound: undefined
            default: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 9
                index: 50
                line: 3
              }
              start: Object {
                column: 7
                index: 48
                line: 3
              }
            }
            variance: FlowVariance {
              kind: 'plus'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 8
                  index: 49
                  line: 3
                }
                start: Object {
                  column: 7
                  index: 48
                  line: 3
                }
              }
            }
          }
          FlowTypeParameter {
            name: 'U'
            bound: undefined
            default: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 12
                index: 53
                line: 3
              }
              start: Object {
                column: 10
                index: 51
                line: 3
              }
            }
            variance: FlowVariance {
              kind: 'minus'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 11
                  index: 52
                  line: 3
                }
                start: Object {
                  column: 10
                  index: 51
                  line: 3
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