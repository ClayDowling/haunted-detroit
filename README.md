# haunted-detroit

Storage repository for Haunted Detroit Campaign. https://claydowling.github.io/haunted-detroit/

## Making Releases

This repository does not store binary artifacts such as PDF files.
Because these are artifacts, they are considered a release.  To make a
release:

- Ensure you have the most recent version of the files. `git pull`

- Commit your changes to character and supporting information files.
   `git commit -am "My most excellent changes"`

- Push your changes to github. `git push`

- Generate the PDF files necessary after your updates to your character
   or supporting files.

- Make an annotated tag, in the format YYYY-MM-DD, which represents the
   day of the last game session.  `git tag -a 2017-12-26 -m "Vampire: the burninating"`

- Push the tag to github. `git push origin 2017-12-26`

- Release by clicking the "Releases" link on the github page.

- Attach all of the binary artifacts for the release.  A session
   summary for release notes is also desirable.
