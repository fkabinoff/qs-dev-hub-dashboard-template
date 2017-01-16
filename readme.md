Qlik Sense card template
========================
The Qlik Sense card template includes a web component named "qliksense-card"
which you can put Qlik Sense objects into and has fullscreen functionality
similar to what you are used to having in the Qlik Sense client. It's easy to use,
and works in dev-hub. You can view a super simple example @ <http://webapps.qlik.com/qliksense-card-example/card-example.html>

Getting started
---------------
This is a working dev-hub template. You can either download this and add it
to your Qlik Sense extensions to use as a template from dev-hub, or use it
as boilerplate for a Qlik Sense mashup. The only thing of note the template really
contains is the qliksense-card component, so you could also simply borrow that and
apply to your own project template.

### Use in dev-hub
Just download this project and install as an extension, and it will be available as a
template selection when creating a new mashup from dev-hub.

### Loading qliksense-card component in your own project
Grab the qliksense-card.html file, and add it to your project, along with the
webcomponents-lite.js file for Polymer. You can use the following cdn for that 
<https://cdn.rawgit.com/download/polymer-cdn/1.7.0.2/lib/webcomponentsjs/webcomponents-lite.min.js>

Using the qliksense-card component
----------------------------------
Using the component is easy.
```html
<!-- Notice the content-height attribute, which you should set 
     to the desired height of the qlik component -->
<qliksense-card content-height="300px">
  <div class="qvplaceholder" id="QV01"></div>
</qliksense-card>
```
That's it. You just wrap your qlik sense object container with the `<qliksense-card>` tag.
