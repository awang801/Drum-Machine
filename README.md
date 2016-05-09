# Drum Machine
TR 808 Drum Machine in HTML5, CSS, and Javascript

Authors: John McCain, Audrey Evans, Hari Ramanan, and Alan Wang

For Prof. Gibbons' EECS 448 class

This drum machine is modeled after the Roland TR808, the classic drum machine that has profoundly effected popular music since it's introduction in the early 1980s.

Sounds are samples of a real TR808 with knobs at several positions (with resolution of 5 samples per knob).  The samples were made by [Michael Fischer & Hyperreal](http://smd-records.com/tr808/?page_id=14).

The MyBufferLoader.js file is based off of [BufferLoader.js](http://www.html5rocks.com/en/tutorials/webaudio/intro/js/buffer-loader.js) from HTML5Rocks.com.

Resources used include JQuery, FontAwesome icons, and jsdoc.

You can access the drum machine [here](http://people.eecs.ku.edu/~jmccain/Project_3/TR808.html).  

Documentation for this project can be accessed [here](http://people.eecs.ku.edu/~jmccain/Project_3/Documentation/index.html).

#Known Bugs

Bug  | Details
------------- | -------------
Responsive Formatting  | Responsive formatting displays incorrectly for certain screen sizes
Mobile Timing  | Timing for beats can be inacurrate on certain browsers, particularly on mobile
Knob Turning | Knobs seem to wobble when being turned
Browser Support | The drum machine doesn't work in some older browsers due to the newer technologies used (like vh/vw css units & the web audio api)
Interrupted/Slow Connection | A slow or unreliable connection will cause the drum machine to fail to load
Tap Tempo/Knob | The tap tempo does not correctly rotate the tempo knob when used (*fixing*)
~~Mobile Labels~~ | ~~Volume knob labels are styled incorrectly on mobile~~ **FIXED**
