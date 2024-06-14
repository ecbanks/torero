# torero

I am experimenting with Torero to get a better sense of how it works. Torero is Itential's free tool to auto-create application execution environments. The use case is for automation artifacts. The problem being solved is that of dependencies.

For example, someone in NetDevOps creates a Python script. They share that script with someone else on the team. The script won't run for that other person because they are missing the right executables or libraries on their system.

Torero handles all of that to make your automation artifact more portable. In the case of our Python script example, Torero will read a standard Python requirements.txt file and use that to build an environment that can run the script.

This repo allows me to do a barebones "hello world" style of test done with torero.

More about torero at https://torero.dev/
