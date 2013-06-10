## springmvc-jpa-quickstart-archtype
A very nice maven quick start arch-type

Use springmvc, jpa(hibernate), jetty9, logback, mysql(hsql) and some other useful and latest libs to start a project.

Provide a content-negotiation view, html, json, or jsonp.

You can try to use http header to reqest a spcific view or you can just use the uri suffix.

For example, .html => html view, .json => json view, .jsonp => jsonp view, default is html view.

Also, provide a spring junit web test case and embed jetty server, you can just code and test in your ide.

Enjoy~

## HOW TO USE
just clone this repo, and use your change your dir in this repo, type `mvn clean install`.
if you have known what' s maven archtype and used it before, you can new -> maven project -> use your local catelog to choose the `spring-jpa-quickstart` -> ok
if not, please try to refer this page -> http://maven.apache.org/guides/mini/guide-creating-archetypes.html
also, you can have to try the command line :-)


## License
This repository is released under [MIT license][].

[MIT License]: http://opensource.org/licenses/mit-license.php
