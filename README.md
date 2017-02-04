#rhizome-interfaces

This repository contain examples to get a minimal [rhizome](https://github.com/sebpiq/rhizome) server working. 

I started messing around with [rhizome](https://github.com/sebpiq/rhizome) and decided to create interfaces for pd and max patchs with simple html elements

I striped down the jquery stuff from the [base](https://github.com/sebpiq/rhizome/tree/master/examples/base) example and got inspired by the [metronome](https://github.com/sebpiq/rhizome/tree/master/examples/metronome) example.  

The way I intend to use this is to be able to have multiple interfaces running on differents devices but having all access to shared control.  
Every interfaces have the sames values.

 

Instructions
--------------

* read and apply rhizome [readme](https://github.com/sebpiq/rhizome)
	* install NPM https://docs.npmjs.com/getting-started/installing-node
	* in a terminal execute : `npm install -g rhizome-server`
	
* clone this repository
	* `git clone https://github.com/gllmAR/rhizome-interfaces` 
	
* go to the example folder in a terminal 
	* example-min is a barebone example with where the interface is staticly build from `page/index.html`
	* example-dynamic is a example where the interface is dynamically build from `page/interface.json`

* run `rhizome config.js` in the selected example folder with a terminal
* open the web page (websocket client)[http://localhost:8000/index.html](http://localhost:8000/index.html).


* these two interaface are designed to work with this pd patch 
	* github.com/gllmar/sigmundBlow

* make your own! 

* there is 4 supported features yet.  
	* label ()
	* hFader (range:slider)
	* push 	(button)
	* progress (progress bar) 

