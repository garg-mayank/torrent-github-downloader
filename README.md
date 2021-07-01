# plz-download
aria2 download + rclone upload = Github offline download

![example](https://raw.githubusercontent.com/ame-yu/plz-download/main/docs/example.gif)
# Usage
1. Fork this project, click on the project workflow and enable it (the following nut cloud as an example)
2. settings->Secrets set RCLONE_CONF (you can search RClone at station B for understanding if you don’t configure it)
    >- RClone configuration file directory
    >- Linux: ~/.config/rclone/rclone.conf
    >- Windows: %USERPROFILE%\\.config\rclone\rclone.conf
3. Create a new wiki page NutStore (the page name should be consistent with the configuration file node name)
4. Edit the NutStore page of the Wiki every time you want to download, write the download address and save the page (multiple lines possible)

[Optional configuration items](https://github.com/ame-yu/plz-download/tree/main/docs)


This project under the [Good Luck With That Public License](https://github.com/me-shaon/GLWTPL)
