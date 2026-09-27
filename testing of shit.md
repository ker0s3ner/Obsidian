# testing of shit



```terminal
language: r
script: |
  # basic vector + stats
  x <- c(4, 8, 15, 16, 23, 42)
  cat("mean:", mean(x), "\n")
  cat("sd:", sd(x), "\n")

  # a simple function
  fib <- function(n) {
    if (n <= 1) return(n)
    return(fib(n - 1) + fib(n - 2))
  }
  cat("fib(10):", fib(10), "\n")

  # data frame + auto-print
  df <- data.frame(id = 1:5, square = (1:5)^2)
  print(df)

  # string ops
  words <- c("nirala", "runs", "r", "now")
  cat(toupper(paste(words, collapse = " ")), "\n")
```



```journal
columns: [Date, Symbol, Side, Entry, Exit, Size, PnL, Tags]
starting_balance: 10000
- 2026-09-01 | AAPL | long | 150.20 | 155.10 | 100 |  | breakout
```


```sql
SELECT 1 + 1 AS answer;
```

```graph
code: your-prismal-share-code
```


```voice
src: voice-1790495116778.webm
title: Voice memo (00:00)
recorded: 9/27/2026, 10:45:20 AM
```


```whiteboard
height: 480
caption: Board
```


