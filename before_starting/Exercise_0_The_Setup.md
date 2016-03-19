#Exercise 0: The Setup
This exercise has no code. It is simply the exercise you complete to get your 
computer to run Ruby. You should follow these instructions as exactly as 
possible. For example, Mac OS X computers already have Ruby 2, so do not install 
Ruby 3 (or any Ruby).

##WARNING
If you do not know how to use PowerShell on Windows, Terminal on OS X, or bash 
on Linux then you need to go learn that first. You should do the exercises in 
Appendix A first before continuing with these exercises.

##Mac OS X
Do the following tasks to complete this exercise:


1. Go to [Text Wrangler](http://www.barebones.com/products/textwrangler/) with your 
browser, get the TextWrangler text editor, and install it.

2. Put TextWrangler (your editor) in your dock so you can reach it easily.

3. Find your Terminal program. Search for it. You will find it.

4. Put your Terminal in your dock as well.

5. Run your Terminal program. It won't look like much.

6. In your Terminal program, run ruby -v to get your Ruby version.

7. If ruby says anything less than "2.0" then your Ruby version is too old. You 
have three choices at this point:

```
Upgrade your OS X to the latest version. It's free now so there's no excuse.

Go to [The Ruby Downloader](https://www.ruby-lang.org/en/downloads/) and try one 
of the installers there.

Ask a friend to help you install Ruby 2.x or greater.
```

8. You should be back at a prompt similar to what you had before you typed 
```ruby -v.``` If not, find out why.

9. Learn how to make a directory in the Terminal.

10. Learn how to change into a directory in the Terminal.

11. Use your editor to create a file in this directory. You will make the file, 
"Save" or "Save As...," and pick this directory.

12. Go back to Terminal using just the keyboard to switch windows.

13. Back in Terminal, can list the directory to see your newly created file.


##OS X: What You Should See

Here's me doing this on my OS X computer in Terminal. Your computer might be 
different, but should be similar to this.

```
Last login: Sat Apr 24 00:56:54 on ttys001
~ $ ruby -v
ruby 2.1.2p95 (2014-05-08 revision 45877) [x86_64-darwin11.0]
~ $ mkdir mystuff
~ $ cd mystuff
mystuff $ ls
# ... Use TextWrangler here to edit test.txt....
mystuff $ ls
test.txt
mystuff $
```

##Windows

1. Go to http://notepad-plus-plus.org/ with your browser, get the Notepad++ text 
editor, and install it. You do not need to be the administrator to do this.

2. Make sure you can get to Notepad++ easily by putting it on your desktop and/or 
in Quick Launch. Both options are available during setup.

3. Run PowerShell from the Start menu. Search for it and you can just press Enter 
to run it.

4. Make a shortcut to it on your desktop and/or Quick Launch for your convenience.

5. Run your PowerShell program (which I will call Terminal later). It won't look 
like much.

6. In your PowerShell (Terminal) program, run ```ruby -v```. You run things in 
Terminal by just typing the command name and pressing Enter.

```
If you run ruby and it's not there (ruby is not recognized..). Install it from 
http://rubyinstaller.org/ or https://www.ruby-lang.org/en/downloads/.

Make sure you install Ruby 2.0 or Ruby 2.1, but not Ruby 1.8 or 1.9.

Close PowerShell and then start it again to make sure Ruby now runs. If it 
doesn't, restart may be required.

You should now see ruby -v print out a version that is 2.1 or 2.0, not 1.9 or 
1.8.
```

7. You should be back at a prompt similar to what you had before you typed ruby. If 
not, find out why.

8. Learn how to make a directory in PowerShell (Terminal).

9. Learn how to change into a directory in PowerShell (Terminal).

10. Use your editor to create a file in this directory. Make the file, Save or Save 
As... and pick this directory.

11. Go back to PowerShell (Terminal) using just the keyboard to switch windows. up 
if you can't figure it out.

12. Back in PowerShell (Terminal), list the directory to see your newly created 
file.

From now on, when I say "Terminal" or "shell" I mean PowerShell and that's what 
you should use.

##Windows: What You Should See

```
> ruby -v
ruby 2.1.2p95 (2014-05-08 revision 45877)
> mkdir mystuff
> cd mystuff

... Here you would use Notepad++ to make test.txt in mystuff ...

>
> dir
 Volume in drive C is
 Volume Serial Number is 085C-7E02

 Directory of C:\Documents and Settings\you\mystuff

04.05.2010  23:32    <DIR>          .
04.05.2010  23:32    <DIR>          ..
04.05.2010  23:32                 6 test.txt
               1 File(s)              6 bytes
               2 Dir(s)  14 804 623 360 bytes free

>
```

It is still correct if you see different information than mine, but yours should 
be similar.

##Linux

Linux is a varied operating system with a bunch of different ways to install 
software. I'm assuming if you are running Linux then you know how to install 
packages so here are your instructions:

1. Use your Linux package manager and install the gedit text editor.

2. Make sure you can get to gedit easily by putting it in your window manager's 
menu.

Run gedit so we can fix some stupid defaults it has.

Open Preferences and select the Editor tab.

Change ```Tab width:``` to 4.

Select (make sure a check mark is in) Insert spaces instead of tabs.

Turn on "Automatic indentation" as well.

Open the View tab and turn on "Display line numbers."

3. Find your Terminal program. It could be called GNOME Terminal, Konsole, or xterm.

4. Put your Terminal in your dock as well.

5. Run your Terminal program. It won't look like much.

6. In your Terminal program, run ```ruby -v```. You run things in Terminal by just typing 
the name and pressing Enter.

If you run ```ruby -v``` and it's not there, install it. Make sure you install Ruby 2.1 
or 2.0 not Ruby 1.9 or 1.8

7. Type ```quit()``` and hit ```Enter``` to exit ruby.

8. You should be back at a prompt similar to what you had before you typed 
```ruby -v.``` If not, find out why.

9. Learn how to make a directory in Terminal.

10. Learn how to change into a directory in Terminal.

11. Use your editor to create a file in this directory. Typically you will make the 
file, Save or Save As..., and pick this directory.

12. Go back to Terminal using just the keyboard to switch windows. Look it up if you 
can't figure it out.

13. Back in Terminal, list the directory to see your newly created file.

##Linux: What You Should See

```
$ ruby -v
ruby 2.1.2p95 (2014-05-08 revision 45877)
$ mkdir mystuff
$ cd mystuff
# ... Use gedit here to edit test.txt ...
$ ls
test.txt
$
```

It is still correct if you see different information than mine, but yours should 
be similar.

##Finding Things on the Internet

A major part of this book is learning to research programming topics online. 
I'll tell you to "search for this on the internet," and your job is to use a 
search engine to find the answer. The reason I have you search instead of just 
giving you the answer is because I want you to be an independent learner who 
does not need my book when you're done with it. If you can find the answers to 
your questions online then you are one step closer to not needing me, and that 
is my goal.

Thanks to search engines such as Google you can easily find anything I tell you 
to find. If I say, "search online for the ruby array functions" then you simply 
do this:

```
Go to http://google.com/
Type: ruby array functions
Read the websites listed to find the best answer.
```

##Warnings for Beginners

You are done with this exercise. This exercise might be hard for you depending 
on your familiarity with your computer. If it is difficult, take the time to 
read and study and get through it, because until you can do these very basic 
things you will find it difficult to get much programming done.

If someone tells you to stop at a specific exercise in this book or to skip 
certain ones, you should ignore that person. Anyone trying to hide knowledge 
from you, or worse, make you get it from them instead of through your own 
efforts, is trying to make you depend on them for your skills. Don't listen to 
them and do the exercises anyway so that you learn how to educate yourself.

If a programmer tells you to use vim or emacs, just say "no." These editors are 
for when you are a better programmer. All you need right now is an editor that 
lets you put text into a file. We will use gedit, TextWrangler, or Notepad++ 
(from now on called "the text editor" or "a text editor") because it is simple 
and the same on all computers. Professional programmers use these text editors 
so it is good enough for you starting out.

A programmer will eventually tell you to use Mac OS X or Linux. If the programmer 
likes fonts and typography, they'll tell you to get a Mac OS X computer. If he 
likes control and has a huge beard, he will (or ze will if you prefer 
non-gendered pronouns of humans with beards) tell you to install Linux. Again, 
use whatever computer you have right now that works. All you need is an editor, 
a Terminal, and Ruby.

A programmer on OS X will try to make you use Homebrew or Macports but you should 
not use these. All you need is Ruby, TextWrangler, and Terminal. Homebrew and 
Macports are for install lots of software in a way that ruins your computer and 
requires more skills to fix than you or your programmer friend have. Avoid it and 
your computer will stay sane while you are working through this book.

A Ruby programmer will tell you to use "idiomatic" Ruby. The word "idiomatic" 
means something different to Ruby programmers than it does to everyone else in 
the world. To you and me "idiomatic" means "a confusing phrase only a native 
speaker would know and should be avoided in well written language". To a Ruby 
programmer "idiomatic" means 
"way.easy.most.natural.people.all.do.unless.real.programmer". The code in this 
book is idiomatic, but it is simple because you are a beginner. When given a 
choice between a Ruby idiom and clear code for a beginner, I chose clear code 
for a beginner. You should tell this Ruby programmer that it's a piece of cake 
to do idiomatic Ruby later when the whole ball of wax is front and center.

Finally, this setup helps you do three things very reliably while you work on the 
exercises:

Write exercises using your text editor, gedit on Linux, TextWrangler on OS X, or 
Notepad++ on Windows.

```
Run the exercises you wrote.
Fix them when they are broken.
Repeat.
```

Anything else will only confuse you, so stick to the plan.