Цель проекта - написать свою версию оболочки bash.
Особенности проекта:
- реализация пайпов и редиректов, в т.ч. множественных;
- написание команд builtin (pwd, env, cd, echo, export, unset);
- улавливание сигналов (игнорирование сигнала Ctrl+\, пустая строка на Ctrl+C, выход из программы при Ctrl+D;
- обработка ошибок и возврат корректного номера ошибки через команду $?
