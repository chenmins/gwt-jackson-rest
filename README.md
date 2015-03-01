gwt-jackson-rest [![Build Status](https://nmorel.ci.cloudbees.com/buildStatus/icon?job=gwt-jackson-rest)](https://nmorel.ci.cloudbees.com/job/gwt-jackson-rest/)
=====
gwt-jackson-rest is a simple GWT REST client using gwt-jackson. It includes an api and an annotation processor which generates an helper class to easily send REST request to an annotated REST service.

Quick start
-------------
Add `<inherits name="com.github.nmorel.gwtjackson.rest.GwtJacksonRest" />` to your module descriptor XML file.

Then annotate your REST service with the annotation `GenRestBuilder`.
An helper class will be generated in the same package by default. You can specify your package by passing the option `package` to the annotation processor.

Check the [example](https://github.com/nmorel/gwt-jackson-rest/tree/master/examples/simple).

Copyright and license
-------------

Copyright 2014 Nicolas Morel under the [Apache 2.0 license](LICENSE).

<img alt="" class="attr__format__media_large attr__typeof__foaf:Image img__fid__7476 img__view_mode__media_large media-image" src="https://www.cloudbees.com/sites/default/files/styles/large/public/Button-Built-on-CB-1.png?itok=3Tnkun-C" style="height:61px; width:178px">
