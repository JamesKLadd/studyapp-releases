# StudyApp releases

Windows installers for StudyApp. The app checks this repo for updates (`releases/latest/download/latest.json`) and
installs only builds signed with the project's update key.

**Install:** download the newest `StudyApp_*_x64-setup.exe` from [Releases](../../releases/latest) and run it. After
that, updates arrive inside the app.

The installers are built here by [.github/workflows/build.yml](.github/workflows/build.yml) from the app's private
source repository.
