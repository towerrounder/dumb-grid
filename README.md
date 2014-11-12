dumb-grid
=========

A dumb responsive grid that behaves exactly the way you tell it to. It does nothing it isnt supposed to do and does everything it needs to do.


Get started
=========

The dumb grid is a simple 12 column grid. Each column is a fraction of it's parent container. Take for example the below layout:

>dumb.dumb-1-1 

>>dumb.dumb-1-3 

>>dumb.dumb-1-3 

>>dumb.dumb-1-3 

This would result in a parent container with three columns.Each 33% width.

>dumb.dumb-1-1

>>dumb.dumb-1-2

>>dumb.dumb-1-2

This would result in a a parent container with two columns. Each 50% width.

The dumb grid as it is contains no margins or padding so nest elements behave exactly how you would expect. For example:

>dumb.dumb-1-1

>>dumb.dumb-1-2

>>>dumb.dumb-1-1

>>>dumb.dumb-1-1

>>dumb.dumb-1-2

This would result in a parent container with two columns. Each 50% width. The left column however contains two columns. Both of wich are 50%.

Dumb grid is responsive. Just use the additional classes.

>xl: 1280px

>lg: 1024px

>md:  768px

>sm:  512px


So for instance, taking the first example, this would result in a container with two columns that are 50% width all of the time:

>dumb.dumb-1-1

>>dumb.dumb-1-2

>>dumb.dumb-1-2

But this would switch into a single column when the screen width is below 1280 (xl)

>dumb.dumb-1-1

>>dumb.dumb-1-2.dumb-xl-1-1

>>dumb.dumb-1-2.dumb-xl-1-1

Optionally there is a pad class as well

>pad: Adds 20px padding all round

>pad-x: Adds 20px padding to left and right

>pad-y: Adds 20px padding to top and bottom











