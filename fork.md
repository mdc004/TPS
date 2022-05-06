# Fork

La funzione fork serve a duplicare un processo dal punto in cui è stata chiamata.

sintassi:

`int result = fork();`

Come si può osservare la funzione restituisce un intero:

- Per la funzione principale, ovvero il padre, restituisce il pid del nuovo processo che è stato duplicato, ovvero il figlio.
- Alla funzione secondaria, ovvero il figlio, restituisce zero.



# Getpid e Get ppid
