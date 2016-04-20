#rhizome-interfaces

This repository contain examples to get a minimal [rhizome](https://github.com/sebpiq/rhizome) server working. 

I started messing around with [rhizome](https://github.com/sebpiq/rhizome) and decided to create interfaces for pd and max patchs with simple html elements

I striped down the jquery stuff from the [base](https://github.com/sebpiq/rhizome/tree/master/examples/base) example and got inspired by the [metronome](https://github.com/sebpiq/rhizome/tree/master/examples/metronome) example.

The way I intend to use this is to be able to have multiple interfaces running on differents devices but having all access to shared control.  Every interfaces have the sames values.

 

Instructions
--------------

* read and apply rhizome [readme](https://github.com/sebpiq/rhizome)
* clone the repository 
* go to the example folder 
* run `rhizome config.js`
* open the web page (websocket client)[http://localhost:8000/index.html](http://localhost:8000/index.html).

* open the pd patch