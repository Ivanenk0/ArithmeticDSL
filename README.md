# Arithmetic DSL
Simple Domain Specific Language (_DSL_) for solving general arithmetic expressions.

> a.k.a. calculator project

Example expression : "1 + (34 * 5)"</br >
Output : 175</br >
Result Tree :
```
expression
└── term
    ├── factor
    │   └── '('
    ├── expression
    │   ├── term
    │   │   ├── factor
    │   │   │   └── NUMBER: 1
    │   │   └── PLUS: +
    │   └── term
    │       └── factor
    │           └── NUMBER: 35
    ├── ')'
    ├── MULTIPLY: *
    └── factor
        └── NUMBER: 5
```

<!-- TODO : add "how to use" topic -->

### Technologies
* Java `17`
* ANTLR `4.13.1`
  * Runtime
  * Tool
* String Template `4.0.8`

### Contact Me

> LinkedIn : [linkedin.com/in/dima-ivanenko/](https://www.linkedin.com/in/dima-ivanenko/)</br >
> E-mail :  [dmytro.ivanenko.contact@gmail.com](mailto:dmytro.ivanenko.contact@gmail.com)</br >
> Telegram Messenger : [@d_ivanenko](https://t.me/d_ivanenko)