# python-fuse-sample

A simple FUSE filesystem example in Python. 

Fork of https://github.com/skorokithakis/python-fuse-sample

## usage

    python passthrough.py root mountpoint
    
Example:

    mkdir myfiles
    touch myfiles/file1
    touch myfules/file2
    mkdir mymountpoint
    python passthrough.py myfiles mymountpoint

The directory myfiles is now mounted at mymountpoint.
    
