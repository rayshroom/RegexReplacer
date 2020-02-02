# RegexReplacer
Replaces file name in batch using human friendly regex

This design is aimed to assist users without regular expression knowledge to replace filenames in a batch. User can drag & drop pre-defined regex tags to find files by name and replace filename based on certain rules.

Regular expressions are represented using easy-to-understand words. All commonly used regex patterns are simplified into words. For example:
- `^` in regex represents start of the line, this design uses `Begin with []` tag to allow users to enter a phrase to search for files start with the phrase. 
- `\d{1,3}(,\d{3})*(\.\d+)?` represents a number that uses thousands seperator, this design allow user to tag of `Numbers` to search for any numbers within the filename.

Other features including add file meta data to part of the filename, also represented in forms of drag & drop tags.


Please refer to the **MainView – After replace.png** file under this directory for a snapshot of the design after user has made a replacement
