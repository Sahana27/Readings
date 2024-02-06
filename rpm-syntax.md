Generic syntax of rpm

Comments 
# this is used a comment.
If we do not want expand macro under comment then use another %
Another option to use is %dnl.

Conditions
Architecture → %ifarch or %ifnarch
Operating system -> %ifos or %ifnos
Conditional expression :%if
Condition ends with %endif
Inside condition block one can use %elif,%ielifarch,%elifos or %else

Preamble tags

Name
Must not include dudewhitespace and may include hyphen.
Name should not include numbers

Version
Consists of alphanumeric string
Tide (~) used to force sorting lower than base

Release 
Used for distinguishing between different builds of the same software version.

Requires
This is used to order the install

Pre:
Denotes dependency to be present before package is installed.
This relates to pre scriplet execution.

Post:
Dependency must be present after the package is installed. Relates to post scriptet execution.

Preun:
Dependency must he present in before the package is in removed. Relates preun scriptet execution

Postun:
Dependency must be present right after the package is removed relates to postun scriptet execution.

Pretrans:
Script must be available before transaction starts.

Postrans:
Script must tre available at the end of the transaction.

Build scriptets:








