# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > do-expressions > scoping-variable`

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
      column: 2
      index: 48
      line: 4
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
          column: 2
          index: 48
          line: 4
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'let'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 2
            index: 48
            line: 4
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
              name: 'x'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 5
                  index: 5
                  line: 1
                }
                start: Object {
                  column: 4
                  index: 4
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 1
                index: 47
                line: 4
              }
              start: Object {
                column: 4
                index: 4
                line: 1
              }
            }
            init: DoExpression {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 1
                  index: 47
                  line: 4
                }
                start: Object {
                  column: 8
                  index: 8
                  line: 1
                }
              }
              body: BlockStatement {
                directives: Array []
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 1
                    index: 47
                    line: 4
                  }
                  start: Object {
                    column: 11
                    index: 11
                    line: 1
                  }
                }
                body: Array [
                  VariableDeclarationStatement {
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 16
                        index: 29
                        line: 2
                      }
                      start: Object {
                        column: 2
                        index: 15
                        line: 2
                      }
                    }
                    declaration: VariableDeclaration {
                      kind: 'let'
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 16
                          index: 29
                          line: 2
                        }
                        start: Object {
                          column: 2
                          index: 15
                          line: 2
                        }
                      }
                      declarations: Array [
                        VariableDeclarator {
                          id: BindingIdentifier {
                            name: 'tmp'
                            loc: Object {
                              filename: 'input.js'
                              end: Object {
                                column: 9
                                index: 22
                                line: 2
                              }
                              start: Object {
                                column: 6
                                index: 19
                                line: 2
                              }
                            }
                          }
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 15
                              index: 28
                              line: 2
                            }
                            start: Object {
                              column: 6
                              index: 19
                              line: 2
                            }
                          }
                          init: CallExpression {
                            arguments: Array []
                            loc: Object {
                              filename: 'input.js'
                              end: Object {
                                column: 15
                                index: 28
                                line: 2
                              }
                              start: Object {
                                column: 12
                                index: 25
                                line: 2
                              }
                            }
                            callee: ReferenceIdentifier {
                              name: 'f'
                              loc: Object {
                                filename: 'input.js'
                                end: Object {
                                  column: 13
                                  index: 26
                                  line: 2
                                }
                                start: Object {
                                  column: 12
                                  index: 25
                                  line: 2
                                }
                              }
                            }
                          }
                        }
                      ]
                    }
                  }
                  ExpressionStatement {
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 15
                        index: 45
                        line: 3
                      }
                      start: Object {
                        column: 2
                        index: 32
                        line: 3
                      }
                    }
                    expression: BinaryExpression {
                      operator: '+'
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 15
                          index: 45
                          line: 3
                        }
                        start: Object {
                          column: 2
                          index: 32
                          line: 3
                        }
                      }
                      right: NumericLiteral {
                        value: 1
                        format: undefined
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 15
                            index: 45
                            line: 3
                          }
                          start: Object {
                            column: 14
                            index: 44
                            line: 3
                          }
                        }
                      }
                      left: BinaryExpression {
                        operator: '*'
                        loc: Object {
                          filename: 'input.js'
                          end: Object {
                            column: 11
                            index: 41
                            line: 3
                          }
                          start: Object {
                            column: 2
                            index: 32
                            line: 3
                          }
                        }
                        left: ReferenceIdentifier {
                          name: 'tmp'
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 5
                              index: 35
                              line: 3
                            }
                            start: Object {
                              column: 2
                              index: 32
                              line: 3
                            }
                          }
                        }
                        right: ReferenceIdentifier {
                          name: 'tmp'
                          loc: Object {
                            filename: 'input.js'
                            end: Object {
                              column: 11
                              index: 41
                              line: 3
                            }
                            start: Object {
                              column: 8
                              index: 38
                              line: 3
                            }
                          }
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
    }
  ]
}
```