### Gist of a JSON Database
Example of how CAMHD metadata might be organized in a json database.

1 file that describes all video files in the archive  
1 file per video that describes all frames in that video  
1 file per video that describes every annotated frame in that video.  

See examples in the repo and listed below.

#### archive_file_meta.json
Contains a list of all video files on the archive and general metadata about each file.

#### CAMHDA301-20160101T000000Z_frame_meta.json
File level list of all frames within a single video file, along with metadata for each frame.

#### CAMHDA301-20160101T000000Z_annotations.json
File level list of all frames within a single video file, along with their annotations.

#### Example way to implement REST API to query JSON database
https://medium.com/codingthesmartway-com-blog/create-a-rest-api-with-json-server-36da8680136d

