# Robot ADD Lab Activity

This is the template text for the Computer ScienceLab Activity.
Most of the content has been copied courtesy of Patrick Totske and is being investigated to provide guidance for the ADD Labs.
Ignore all of the Content below

This is the interactive web version of the lab, that gives you a terminal and a working java environment.
Lab exercises are also available as PDF on Canvas should you wish to work on your own computer without the distractions.

## Listing Files in the web environment

On the right you should see two windows: the *text editor* that shows our very first Java program named `Hello.java`, and right below that there is a *terminal window*.

Click the folder icon, and you'll see two files, `Hello.java` and one called `Comp122.class`, which we will use later. Click the folder icon again to hide all that.


Next, in the terminal window, immediately to the right of the dollar sign (`$`), type precisely the below (in lowercase), then hit Enter:

```
ls
```

You should see two files again. That's because you've just listed the files in that same folder, this time using a command-line interface (CLI), using just your keyboard, rather than the graphical user interface (GUI) represented by that folder icon. In particular, you *executed* (i.e., ran) a command called `ls`, which is shorthand for "list" (it's such a frequently used command that its authors called it just `ls` to save keystrokes). Make sense?

Here on out, to execute (i.e., run) a command means to type it into a terminal window and then hit Enter. Commands are "case-sensitive," so be sure not to type in uppercase when you mean lowercase or vice versa.

{% next %}

## Compiling Programs

Now, before we can execute the program at right, recall that we must *compile* it with a *compiler* (e.g., `javac`), translating it from *source code* into machine executable binary code.
Execute the command below to do just that:

```
javac Hello.java
```

And then execute this one again:

```
ls
```

This time, you should also see a file named `Hello.class` listed as well (you can see the same graphically if you click that folder icon again)? That's because `javac` has translated the source code in `Hello.java` into java *bytecode* in `Hello.class`.
Bytecode can be interpreted by the Java Virtual Machine (JVM).
