# NDeid

NDeid is a standalone identification scrubber program which doesn't require tensorflow installation or word embeddings download. Currently this program has two versions, Mac & Linux.
(For Mac compatible version: https://github.com/klee70/NDeid_mac)


## Using NDeid

To use NDeid, download the repository into ZIP file and run the following commands from the terminal: 
```
unzip NDeid-master.zip
cd NDeid-master
unzip lib.zip
```

To get offsets of PHIs from '.txt' files, place target files under 'NDeid-master/target' folder.

```
(For Linux)
./NDeid_linux > result.txt
```
