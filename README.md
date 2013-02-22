CTFWriter
=========

A Common trace format writer

This is basically a printf to ctf writer

Here is the "Roadmap" for that. 

A- A writer to CTF straight to the hdd. 
B- Buffering - Store the events in packets of 64KB then write it to disk. 
C- More Buffering - Write to a network socket or something... I don't care. Then have a daemon get it out. Make the daemon low priority. 
D- Better tracepoint support.
