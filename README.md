# Programação Funcional em Scheme & Haskell
Repositório para armazenar os códigos em Haskell e Scheme da disciplina de Programação Funcional da Universidade de Fortaleza:
```
> (define (conta-nao-zero list) 
    (if (= car(list) 0) 
        conta-nao-zero cdr(list)
        (+ 1 conta-nao-zero cdr(list))   
    ) 
  )
``` 
