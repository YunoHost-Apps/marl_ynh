MARL runs in local mode by default, i.e. it processes all data within the user's browser and nothing is sent to the server.

However, MARL can also be run in Server mode, which enables users authorized to access this app to view a Mastodon archive stored at a given location.
To enable the Server mode, one or several paths to Mastodon archives must be filled in in the configuration panel.
Each Mastodon archive file you link to must be unpacked at the given location (it could be for instance on this server at `/home/yunohost.app/marl` if you want the Mastodon archive to be backed up together with the app by default).
If you plan to share a MARL server instance, you might want to purge the archive from its private messages (the tool `outbox cleanup` ([GitHub link](https://github.com/s427/MARL/blob/main/tools/outbox-cleanup/readme.md) can be used for that purpose).
