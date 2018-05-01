# R Programming


#### Set Up Bits 
- ```getwd()``` is a command that gets you the working directory 
- ```dir()``` displays all of the files within the working directory

Your files and R files must be in your working directory for you to access it.
You can change your working directory by hitting the Misc option

The nice thing about R on the mac is that it comes with a built in text editor!

I can type the following example function,
```
myfunction <- function(x) {
	y <- rnorm(100)
	mean(y)
}
``` 
into the R console, press enter, and have the function saved as an object in my directory
(command ls() displays all files in working directory.
