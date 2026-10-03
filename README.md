# Application Sender for Windows

[Download the latest installer](https://github.com/Dkillington/ApplicationSender-Releases/releases/latest)

Application Sender is a native Windows app for importing a resume, finding relevant jobs on selected Greenhouse and Lever company boards, and tracking application outcomes. Automatic submission is available for authorized Greenhouse integrations with supported forms.

## Install

Download **Dkillington.ApplicationSender-win-Setup.exe** from the latest release. Choose a writable installation folder with Browse or enter a path, then click Install. The app includes its .NET desktop runtime. Windows x64 is supported. Installers are currently unsigned.

An existing installation folder is remembered by Setup. For command-line installation, use `--installto "D:\Apps\Application Sender"`; `--silent` is also supported. The portable ZIP is available if you prefer extracting the app.

## Update

Open **Settings → App updates**, click **Check for updates**, read the description, and choose **Download update**. Click **Restart to update** when ready. Updates use the existing installation folder, including a custom path, without asking for it again. Downloaded updates can also apply on the next launch.

Your profile, resume, and application history remain separately under `%LOCALAPPDATA%\ApplicationSender`. Settings and history are saved before an update restart. Update controls wait while a job run or resume import is active.

Each completed app change is released with a new version and a description. Release assets include the installer, portable ZIP, full update package, update feed, and SHA256 checksums. This public repository distributes downloads; source is maintained privately.
