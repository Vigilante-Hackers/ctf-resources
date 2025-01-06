# Binary Exploitation

This is the old school hacking, the most original form. The challenges here are
often as follows:

- There is a netcat server running on the challenge machine which you have to
  connect to.
- A copy of the binary running on the server, often with a dummy flag, may be 
  provided to you. It is to help you exploit the netcat server and get the flag.
- You have to give an input that gets you the flag (or in some cases lands you
  a shell), and then you submit the flag.

You might be wondering how just a text input can lead to all of this, it's 
because that's the beauty of a buffer overflow :) There are many techniques 
involved, and it becomes fairly complex as the difficulty of the challenges 
progess.
