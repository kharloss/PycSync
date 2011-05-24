PycSync: A python flickr photo uploader

Python depencencies:
- flickrapi
- pyyaml

Put your flickr api keys in ~/.pycsync
 flickr_api: [api_key, secret]

Then, create a directory of photos. Place a PycSync.yml file in that dir.
PycSync.yml should look like this:
 album: Title of Flickr Set
 is_public: 0
 is_family: 1
 is_friend: 1

Run pycsync.py in the directory you wish to sync to flickr.
Upload status will be saved in PycSync_meta.yml.