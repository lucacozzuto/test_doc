.. _first-page:

*******************
First Page
*******************

Small title for the first paragraph
============
Add some text about the first paragraph

Another title for the second paragraph
============
Add some text about the second paragraph

Here an image

.. image:: images/test.jpeg
  :width: 400
  

Here a sub paragraph
----------------
Add some text about the sub paragraph. And here a `Link <https://www.google.com>`. 

Some code below that will be interpreted as **console**

.. code-block:: console

	echo hello world

Other code that can be higlighted as **groovy**

.. code-block:: groovy

	#!/usr/bin/env nextflow
	// This is a comment

	/*
	 * This is a block of comments
	 */

	// This is needed for activating the new DLS2
	nextflow.enable.dsl=2

	//Let's create a channel from string values
	str = Channel.from('hello', 'hola', 'bonjour')

	/*
	* Let's print that channel using the operator view()
	* https://www.nextflow.io/docs/latest/operator.html#view
	*/

	str.view()

