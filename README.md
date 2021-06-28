##Description

Get Suffixing App project from Logging topic. Make its output structured.

_App Specification_

It is a Suffixing App - a small java application that refers to a config file and renames a set of files and renames them adding a suffix specified in the same config.

Changes: config file now should be an XML file.

**Details:**

1.Application should read a config file on the startup
2.Then it should ensure that all of files from the config exist
3.Then it should rename each file adding a suffix from the config to its name


**Logging spec of previous exercise:**

-Application should log startup information.
-Application should log information on config read.
-Application should log renaming process information.
-Application should log summary information.
-Application should log shutdown information.
-Application should handle and log possible errors.
Use different logging level. All log entries should contain a date and time information as well.

Changes:

1.When renaming is finished the application should print a document of completed actions.
    Document should be XML-based. It should contain:
    -config file name
    -execution time
    -list of files with old and new names
2.All the logging entries from previous exercise should become JSON document of some structure. They should contain:
    -date and time
    -message
    -severity label
    -error info, if its error

**Steps**

1.Complete the project to meet specifications from previous exercise.
2.Show the mentor your results.