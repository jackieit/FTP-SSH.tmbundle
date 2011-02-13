check out into a folder called FTP:SSH.tmbundle (github doesnt allow this to be the repo name)
# cd '/Users/<your user name>/Library/Application Support/TextMate/Pristine Copy/Bundles'
# git clone git://github.com/craigulliott/FTP-SSH.tmbundle.git  FTP\:SSH.tmbundle

== My Changes ==

* added ability to upload and download using curl ftp rather than generic ftp. I was having issues uploading to a media temple dedicated server, and curl worked better for me. just change the protocol be "curlftp" and it will utilize curl. 
