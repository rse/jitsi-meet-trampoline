
[Jitsi Trampoline](https://rse.github.io/jitsi-trampoline/)
===========================================================

About
-----

[Jitsi](https://jitsi.org/) is a powerful peer-to-peer (P2P) or
Selective Forwarding Unit (SFU), [WebRTC](https://webrtc.org/) based, browser based,
Open Source video conferencing solution. It can also be used
for bringing the video/audio streams of presenters into a live event
production software like [OBS Studio](https://obsproject.com) or
an ingest software like [Vingester](https://vingester.app).
This form is just a parameter simplification trampoline, i.e., it takes a few intuitive URL
parameters and starts the underlying complex technical API of
[Jitsi Meet](https://jitsi.org/jitsi-meet/). By default it uses the
free [meet.jit.si](https://meet.jit.si/) service.

This allows you to control [Jitsi Meet](https://jitsi.org/jitsi-meet/)
parameters at a central place while being able to use clean,
intuitive and stable URLs for both the presenters and [OBS
Studio](https://obsproject.com) or [Vingester](https://vingester.app).
The underlying [Jitsi Meet](https://jitsi.org/jitsi-meet/) parameter
sets are rather opinionated and hard-coded and are intended for meeting
or broadcast sessions with multiple presenters only.

Installation
------------

There is no installation needed if you are using the Github URL
https://rse.github.io/jitsi-meet-trampoline/. If you want to
use a different URL, then copy the files [index.html](index.html)
and [jquery.js](jquery.js) to your own website.

License
-------

Copyright &copy; 2021 [Dr. Ralf S. Engelschall](http://engelschall.com/)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

