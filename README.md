tut-releaseNotesFromTags
========================

Simple tutorial repo that shows how to create beautiful release notes with git, gradle and markdown

## Running this example

```
./gradlew releaseNotes
```

this will create two files

* releaseNotes.md
* releaseNotes.html

Open the file `releaseNotes.html` in your browser to see the outcome

## Adding your own tags for testing

You *must* add annotated tags with the flag `--cleanup=verbatim` to suppress the interpretation of # as comment in commit messages
