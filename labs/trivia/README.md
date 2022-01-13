# Lab 1: Getting Started

## Open VS Code.

## Download starter code

Start by clicking inside your terminal window, then execute cd by itself. You should find that its “prompt” resembles the below.
```
$
```
Click inside of that terminal window and then execute
```
wget https://cdn.cs50.net/2021/fall/labs/8/trivia.zip
```
followed by Enter in order to download a ZIP called trivia.zip in your codespace. Take care not to overlook the space between wget and the following URL, or any other character for that matter!

Now execute
```
unzip trivia.zip
```

to create a folder called trivia. You no longer need the ZIP file, so you can execute
```
rm trivia.zip
```

Now type
```
cd trivia
```

followed by Enter to move yourself into (i.e., open) that directory. Your prompt should now resemble the below.
```
trivia/ $
```

If all was successful, you should execute
```
ls
```

and you should see an index.html file and a styles.css file.

If you run into any trouble, follow these same steps again and see if you can determine where you went wrong!
