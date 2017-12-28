# Graphplan
Carnegie Mellon University Graphplan Impl

## First Steps

### Compile (on Linux)

    ~/cmu-graphplan$ cd source
    ~/cmu-graphplan/source$ make

### Exec example (on Linux)

    ~/cmu-graphplan$ source/graphplan -o tasks_ops.txt -f tasks_facts.txt -d
    
### Additional info

Check out the [wiki](https://github.com/juan-vg/cmu-graphplan/wiki)

## Tasks Example Domain & Problem

Just my own proof of concept whose purpose is to test the algorithm. Furthermore, in order to check the plan's parallelism possibilities, the example has been designed to force this result. Have a look at the following diagram!

![Tasks Diagram](https://github.com/juan-vg/cmu-graphplan/blob/master/tasks-example-diagram.png)

In addition, having the goal of getting alternative plans in mind, you will find an [ops file](tasks_ops_t5_fails.txt) that simulates a task failure. 

# Graphplan Impl. Credits

User avrim from CMU

http://www.cs.cmu.edu/~avrim/graphplan.html

http://www.cs.cmu.edu/afs/cs.cmu.edu/usr/avrim/Planning/Graphplan/
