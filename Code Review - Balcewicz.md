#Code Review

#General Review Checklist

#Purpose

##Is the purpose of the project is clear?

The README clearly describes the purpose of the project. The difference between this project and prior works is clearly explained.

##Is it clear what each file in the project is intened for?

There is currently a duplicate of the LR_Model.Rmd script in the Scripts folder that is outdated. Otherwise each file and filepath makes sense.

##It is clear how the various files interact?

Yes. Each of the files in the Data folder is loaded by LR_Model.Rmd

##Is it clear what the purpose if of specific sections of code?

Yes. The code is clearly commented within the chunks.

##How well commented is the code on a scale of 1(no comments) to 10(very well commented).

8

##How can the purposes of the project and files be improved?

More explanation of the plots could be included.

#Organization

##Is the project organized such that you can intuit where the data, scripts, and output files are stored?

There is currently a duplicate of the LR_Model.Rmd script in the Scripts folder. I would also save the final image plots in a separate images folder.

##Approximately how much time did it take you to understand the work flow in the project?

About 5 minutes

##How well defined are code chunks in the project?

Very well defined. I think they are just the right size to run quickly and have a meaninful output each.

##How can organization be improved?

I would add bolded section headers with markdown defining the individual sections of the project, like loading data and packages, creating glms, and creating spatial plots.

#Functionality

##Does the code appear to advance the purpose of the project?

Yes. The code in LR_Model.Rmd matches with the purpose outlined in the README.

##Do the existing components of the project appear to function?

The main LR_Model.Rmd in the main directory functions, but not the one in the scripts folder. It should be overwritten.

##How can the author improve functionality of code?

I would consider adding back in an install.packages command as is in the LR_Model.Rmd in the scripts folder so it is easier for others to run this code.

#Specific File Comments

README.md

I think it is well written, but I had to google a couple of terms because it requires some domain-specific knowledge that I don't have. I would consider addding links to previous papers in the field about this topic that this work builds on.

LR_Model.Rmd

It is not my personal preference to have the code comments inside the code chunks in a Rmd file, but since that's your preference, I think it's ok. I would add bolded headers and knit this to HTML or PDF for readers.
