# Lua 'error' Function and Call Stack Levels

This example demonstrates a potential issue with Lua's `error` function when specifying the error level.  The second argument to `error` controls the stack level at which the error is reported.  Improper usage can lead to confusing error messages.

The file `bug.lua` contains the code exhibiting the issue. The file `bugSolution.lua` shows how to resolve the problem.