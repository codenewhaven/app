## Goal

Hi everyone,

Our goal is to build a simple app, as discussed in class. Main features:

- Home page
    + Links to internal pages
    + Links to other resources
- Calendar
    + All school events
    + Classes (individual)
- Delays/school cancellation
- Contact info (structured, sortable)
    + Teacher emails
    + Student council members and emails
- City resources
    + Bus schedule
    + Public services contact info
- Community service hours tracker
    + Email with photos of community service forms

The easiest way to build this app is to build it as a mobile-optimized website.

On a website, pages are either **static** or **dynamic**. A static page, like
a list of links, does not change in response to user input. A dynmic page, like
a calendar or community service tracker, changes when the user interacts with it.

Here's our list of features, divided by static and dynamic:

### Static pages

- Home page
    + Links to internal pages
    + Links to other resources
- City resources
    + Bus schedule
    + Public services contact info
- Contact info 
    + Teacher emails
    + Student council members and emails

### Dynamic pages

- Calendar
    + All school events
    + Classes (individual)
- Community service hours tracker
    + Email with photos of community service forms

You might notice that the static pages are the easiest to build. Essentially
they are going to be a list of links. You know how to do this.

## Plan of attack

We want to complete the static pages before we complete the dynamic pages. This is because static pages are easier to code and will give us a good starting point.

So, we have three static pages we want to make. Let's break into teams.

### Team 1: home page (index.html)

Responsibilities:

- Insert links to internal pages (city.html, contact.html)
- Write some text describing the app

### Team 2: city resources (city.html)

Responsibilities:

- Collect data on city resources (i.e., find links to include)
- Insert list of links to city resources

### Team 3: contact info (contact.html)

Responsibilities:

- Collect emails to include
- Insert links to email. Use `mailto:` links to open email programs

## Working on the code

This repository contains the three files you need to get started. Each team
should only work on one file, as described above.

You edit these HTML files just like we did in the fall. Reminder:

### Step 1: Clone repository

1. Open terminal (`Cmd + Space`, type `Terminal` into spotlight)
2. `cd ~/Desktop` (or your personal folder)
3. `git clone https://github.com/codenewhaven/app`
4. `cd app`

Note: You can also do all git steps with the github mac app, which should be downloaded,
and relatively easy to use. I do not have the instructions offhand.

### Step 2: Edit files and view changes

Now you downloaded the files (in the folder `app` on your desktop), you can edit them in your text editor, just like we did in the fall. When you want to
see them in action, go to your browser, and `cmd + O` to open the files, just
like we did in the fall. 

### Step 3: Commit changes

After you change a file and are ready to share with the class, you need to 
commit your changes, and then push them to the repository. Remember, you can
do this with the github app, or the command line. Here are the command line
instructions:

1. Open terminal (`Cmd + Space`, type `Terminal` into spotlight)
2. `cd ~/Desktop` (or your personal folder)
4. `cd app` (should already be here from cloning it)
5. `git status` to see changes since last time
6. `git add .` to add any new files
7. `git commit -am "my commit message"` to commit
8. `git push` to push files to github

### Step 4: Sync your classmate's changes

After your classmates or other groups push changes, you can pull them down
to your computer. Command line instructions:

1. Open terminal (`Cmd + Space`, type `Terminal` into spotlight)
2. `cd ~/Desktop` (or your personal folder)
4. `cd app` (should already be here from cloning it)
5. `git pull` to pull the changes

As long as you did not change the same files, you should now have your classmates' new files.

## Resources

Everything you learned in the fall!

https://github.com/codenewhaven/mba-website
