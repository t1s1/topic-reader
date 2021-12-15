# topic-reader
inspired by zgutterm/Reader

## Cloner
Searches repos for courses and downloads them for use by Topic Reader

## Topic Reader
Searches recursively for dco.yml files. Then gets the asciidoc files lectures, GEs, and Quizzes. Each of those get a reading time calculated, and this is summed to a reading estimate by topic (in minutes).

Edit config.ini to change consumption speeds and values.

Output is a set of tab-separated values: course, chapter, topic, estimate
