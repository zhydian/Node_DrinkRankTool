# Welcome to Drink Voting Tool (DVT) 1.0!

This tool was created to take the previously tallied votes and assign points to each candidate then output the results to the console or to a file


# Requirements

 - Node  
	 - [Package](https://nodejs.org/dist/v10.16.0/node-v10.16.0.pkg)	
	 - [Installation Instructions](https://www.webucator.com/how-to/how-install-nodejs-on-mac.cfm)
 - Git: Software repository which holds the files for Drink Voting Tool.
	 - [Package](https://git-scm.com/download/mac)
	 - [Installation Instructions](https://www.atlassian.com/git/tutorials/install-git)

##  Downloading DVT 1.0

1. Verify Installation of Node and Git
	Type the following commands into the console. If it shows the installed version number then you did it correctly!
	Node: **$ node -v**
	Git: 		**$ git --version**
2.	Type the following command in the console in order to download DVT 1.0 in your present directory
	**$ git clone https://github.com/substantial-candidates/zhydian.git**
3. Don't forget to change directory into the directory that was created for you.
4. Install Dependencies of DVT
	5. Type **$ npm install** while in the folder that was created when DVT was downloaded.

    
## Usage

1. View results in command window using default file (sample-input.txt)
	 **$ node app.js**
2. View results in command window using specified file
	**$ node app.js "specified file"**
3. Output results to file
	**$ node app.js "specified file" > "outputfile.txt"**
	Don't forget to replace the words inside the quote with your specified file names.

## Testing DVT
1. Testing DVT is simple. Type the following command in the root directory of the project

	**$ npm run test**

If you have any questions and are ready to schedule me for the interview email at mathew.mozer@gmail.com




## Original Code Challenge

This is a small problem that we would like you to solve so that we can get an
idea of your coding ability. Your submission will be run in a clean environment
to see if it produces the expected output. Please be sure to provide
instructions for installing any dependencies.

### What we look for

We will be looking at the quality and professionalism of your work. In
particular we look for clean, well-designed, maintainable code. Although this is
a rather small task, it should be approached as you would an actual task for a
customer.

## The Problem

A special event to taste and rate new LaCroix flavors is happening. Attendees
have been asked to rank the new flavors from most to least favorite.

We want you to create a command-line application that will determine what new
flavors are performing best.

### Input/Output

The input and output will be text. Your solution should parse the provided
sample-input.txt file via stdin (pipe or redirect) or by parsing a file passed
by name on the command line. Your solution should output the correct result via
stdout to the console.

The input contains results from three attendees. Each line has the flavor and
the rank from 1 to 5. See sample-input.txt for details. The output should be
ordered from most to least preferred, following the format specified in
expected-output.txt.

You can expect that the input will be well-formed. There is no need to add
special handling for malformed input files.

### The Rules

5 points should be given to an attendee's favorite flavor, 3 points to their
second favorite, 2 points to their third favorite, 1 point to their
fourth favorite and 0 points to their fifth favorite.

Nothing beats genuine flavor (or lack thereof), but if two flavors are ranked
equally then our marketing department would prefer us to choose the flavor with
the shorter name for increased tweetability.

### Guidelines

This should be implemented in a language with which you are familiar. We
would prefer that you use Javascript, Ruby, Elixir, Python, Swift, or Kotlin,
if you are comfortable doing so. If none of these are comfortable, please
choose a language that is both comfortable for you and suited to the task.

Your solution should be able to be run (and if applicable, built) from the
command line. Please include appropriate scripts and instructions for running
your application and your tests.

If you use other libraries installed by a common package manager
(RubyGems/Bundler, npm, pip, Gradle), it is not necessary to commit the
installed packages.

We write automated tests and we would like you to do so as well.

We appreciate well factored, object-oriented or functional designs.

Please document any steps necessary to run your solution and your tests.

### Platform Support

This will be run in a unix-ish environment (OS X). If you choose to use a
compiled language, please keep this in mind. (Dependency on Xcode is
acceptable for Swift/Objective-C solutions) Please use platform-agnostic
constructs where possible (line-endings and file-path-separators are two
problematic areas).


