# `execlock`

Some funny goroutine lock.

## `SingleWaitExec.Do`

do an operation:
* If nothing is running, then run it
* If something is running, then just wait it

## `SingleExec.Do`

do an operation:
* If nothing is running, then run it
* If something is running, then just do nothing

## `SingleLatestExec`

do an operation:
* If nothing is running, then run it
* If something is running, then stop the last and run the new
