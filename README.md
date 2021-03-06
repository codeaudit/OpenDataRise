<p align="center">
<img alt="opendatarise" src="https://github.com/opendatatrentino/OpenDataRise/wiki/images/odr-logo-with-writing-on-top-700px.png" width="300px">
</p>
Data integration tool to cleanse and semantify datasets from CKAN repositories. Based on [OpenRefine](https://github.com/OpenRefine/OpenRefine).

<p align="center">
  <img alt="" width="60%" src="https://github.com/opendatatrentino/OpenDataRise/wiki/images/promo-screenshot.png"/>
</p>

**Project status**: Developing - we are developing and testing using reconciliation sevices of DISI, University of Trento. 
Currently code is developed in a private repository, when project reaches a sufficient level of stability we will merge changes into the public repo. We keep [public wiki](https://github.com/opendatatrentino/OpenDataRise/wiki) updated, though, so you can get an idea of how the project will look like. A video of a prototype using Freebase and DataTXT reconciliation services can be <a href="https://docs.google.com/file/d/0B3zPB8ad298hWEYxZ2VMX0p5a0k" target="_blank">watched here</a>


**Additions to OpenRefine:**

 * a workflow subdivided in steps
 * an interface to import datasets from [ckan repositories](http://ckan.org/) and also to visualize resources stats taken with [Ckanalyze](https://github.com/opendatatrentino/CKANalyze)
 * suggestions on operations to do based on schema
 * enhanced data validation with column types
 * multivalued cells support
 * semantic tagging of natural language text
 * online help system 
 * maven as dependency management system instead of Ant
 * WAR deployable on Tomcat as build output instead of Refine custom old Jetty server
 * interactive debugging support with a recent version of Jetty
 * enhanced event system for plugins
 * possibility for plugins to attach data to columns, cells and rows


**Roadmap**: see [project issues](https://github.com/opendatatrentino/OpenDataRise/issues)

**Documentation**: see [the wiki](https://github.com/opendatatrentino/OpenDataRise/wiki)



**Platform** 

* Java server with [Butterfly framework](https://code.google.com/p/simile-butterfly/)
* Browser interface done in [JQuery UI](http://jqueryui.com/)
* Maven is used for dependency management




### Credits


OpenDataRise adds a semantic layer upon the OpenRefine platform, so it owes a great deal of gratitude to OpenRefine authors. 

##### OpenDataRise contributors:

 - David Leoni - Trento RISE david.leoni@trentorise.eu
 - Juan Pane - DISI at University of Trento - pane@disi.unitn.it
 - Ivan Tankoyeu - tankoyeu@disi.unitn.it
 - Alberto Zanella - Trento RISE - alberto.zanella@trentorise.eu
 - Moaz Reyad - DISI at University of Trento - moaz.reyad@unitn.it
 
 
##### OpenRefine contributors:

Refine was created by Metaweb Technologies, Inc. and originally written
and conceived by David Huynh <dfhuynh@google.com>. Metaweb Technologies, Inc.
was acquired by Google, Inc. in July 2010 and the product was renamed Google Refine.
In October 2012, it was renamed OpenRefine as it transitioned to a 
community-supported product. 

This is the full list of Open Refine contributors (in chronological order):

 - David Huynh <dfhuynh@google.com>
 - Stefano Mazzocchi <stefanom@google.com>
 - Vishal Talwar <vtalwar@google.com> 
 - Jeff Fry <jfry@google.com>
 - Will Moffat <wdm@google.com>
 - James Home <jameshome@google.com>
 - Iain Sproat <iainsproat@gmail.com>
 - Tom Morris <tfmorris@gmail.com>
 - Heather Campbell <campbellh@google.com>
 - Thad Guidry <thadguidry@gmail.com>
 - Paul Makepeace <paulm@paulm.com>
 - Tomaž Šolc <tomaz.solc@zemanta.com>
 - Gabriel Sjoberg <GabrielSjoberg@gmail.com>
 - Rod Salazar <rodrod.salazar@gmail.com>
 - pxb <pxb1988@gmail.com>




