History
=======

0.2.0 2009-10-23
----------------

**enhancements**

- No More Forking! The event loop used to fork to ensure signal handlers would be observed.
  A custom signal handling solution has replaced the need to fork.
- The Event listener can now be stopped and restarted using FSEvent#stop and FSEvent#restart

**deprecations**

- FSEvent#run now FSEvent#start


0.1.0 2009-10-15
----------------
- Listen for events using OSX's FSEvents API

