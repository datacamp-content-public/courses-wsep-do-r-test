---
title: 'Wprowadzenie do pakietu R'
description: ""
free_preview: true
---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

R to język programowania, ale jednocześnie 

`@instructions`
Wykonaj polecenie, które widzisz w oknie obok.

`@hint`


`@pre_exercise_code`
```{r}
# zmienna liczbowa 
liczba <- 1

#zmienna tekstowa
tekst <- "abcs"

# pomnóż dwie zmienną liczba przez 2 i zapisz do zmiennej iloczyn
```

`@sample_code`
```{r}
# zmienna liczbowa 
liczba <- 1

#zmienna tekstowa
tekst <- "abcs"

# pomnóż dwie zmienną liczba przez 2 i zapisz do zmiennej iloczyn

```

`@solution`
```{r}
# zmienna liczbowa 
liczba <- 1

#zmienna tekstowa
tekst <- "abcs"

# pomnóż dwie zmienną liczba przez 2 i zapisz do zmiennej iloczyn
iloczyn <- liczba * 2
```

`@sct`
```{r}
ex() %>% check_object("iloczyn") %>% check_equal()
```
