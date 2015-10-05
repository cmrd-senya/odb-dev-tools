# odb-dev-tools
Helper tools for Open Document Database (*.odb) inspection.

This tools will unpack an .odb file for you and create a git repository. Then you can figure out changes and control it in the document using git.

## Usage

```
host:/home/user$ source odb-dev-tools/odb-dev-tools
host:/home/user$ odb_init test.odb # creates a repository with a document content
...
host:/home/user/test.odb-dev$ odb_update # updates a repository from a document when you've changed it
...
host:/home/user/test.odb-dev$ odb_build # packs the content from a repository back to a document
```

## Dependencies
* bash
* git
* zip/unzip
* xmllint
