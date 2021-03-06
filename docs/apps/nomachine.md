## NoMachine

The NoMachine Client enables remote graphical work on CSC supercomputers
from your local computer. The speedup vs.
X11 (native or emulated) can be many fold, so you will experience
substantial improvement. Note that with NoMachine you don't need
X-emulators or X-term (in Linux).

[TOC]

![NoMachine sketch][NoMachine sketch]

## Available

The client is installed on your local machine, and the version 6 NoMachine
Enterprise Terminal Server runs on nxkajaani.csc.fi.

## License

The NoMachine *client* is free and access to nxkajaani.csc.fi is
allowed for all CSC users. 

## Usage

NoMachine is used to connect from your local computer
to nxkajaani.csc.fi, a gateway running a NoMachine server. There a simple 
Desktop enables you to ssh to CSC supercomputers. A NoMachine client
is available for Win, Mac, Linux.


1.  You will need a user account at CSC (on the server where you run
    applications). If you don't have one, you can get it from [here].
2.  Download the latest NoMachine _Client_ (win, mac, linux) from the
    NoMachine site. Don't download the _Desktop_.
3.  Install and configure your NoMachine client. See [CSC NoMachine Tutorial]
4.  Start the NoMachine client and log on to nxkajaani.csc.fi.
5.  Right click in the Desktop and choose the CSC server you want to use
    (opens an ssh terminal).
6.  Start working on great science.
7.  When you're done, disconnect or terminate the connection from the
    Desktop top right corner (peel menu). The number of overall sessions,
    including suspended ones, is limited to one per user.

## More Information

* NoMachine [knowledge base](https://www.nomachine.com/knowledge-base)
* User support via CSC through servicedesk@csc.fi

  [NoMachine sketch]: /img/nomachine.png
  [here]: /accounts/how-to-create-new-user-account
  [CSC NoMachine Tutorial]: /support/tutorials/nomachine-usage
