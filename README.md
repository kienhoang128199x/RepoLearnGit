clear
sub add 1
sub add 2
main add 1
main add 2
before rebase
main: clear -> main add 1 -> main add 2
sub: clear -> sub add 1 -> sub add 2
after rebase (from main, run "git rebase sub")
main: clear -> sub add 1 -> sub add 2 -> main add 1 -> main add 2


