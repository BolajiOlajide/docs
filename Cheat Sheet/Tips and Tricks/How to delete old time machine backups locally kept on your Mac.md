
### Delete Time Machine Local Snapshots

Did you know that your Mac keeps a local copy of your Time Machine backups in case your external drive becomes unavailable? Your Mac will keep them until space is needed. Why wait until the storage is running out before cleaning them up? You can clean them manually.

Here are the steps:

1.  Open Terminal via [Spotlight](https://www.drbuho.com/how-to/rebuild-spotlight-index) or Launchpad.
    
2.  Type in: `tmutil listlocalsnapshotdates`, press the Return key on your keyboard, and you'll find a list of backups sorted by date.
    
    ![](data:image/svg+xml,%3csvg%20xmlns=%27http://www.w3.org/2000/svg%27%20version=%271.1%27%20width=%271170%27%20height=%27730%27/%3e)![Find Time Machine Backups on Mac](https://www.drbuho.com/_next/image?url=https%3A%2F%2Fwww.drbuho.com%2Fstr-api%2Fuploads%2Ffind_time_machine_snapshots_on_mac_bf958d36f6_c1ddeb660f.png&w=3840&q=95)
    
3.  To delete a backup, type this command into the Terminal: `tmutil deletelocalsnapshots "xxxxxxx"`, enter the password for the user account if asked, and press Return. (Note: "xxxxxxx" stands for the date of the backup you want to remove.)
    
    `e.g. tmutil deletelocalsnapshots 2021-07-19-095939`

Repeat step 3 if you want to delete any or all snapshots.