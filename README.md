# RHMAP-Demo-Apps
## RHMAP-RSS-Reader-Demo
This is a [demo project](https://github.com/mmetting/RHMAP-RSS-Reader-Demo) utilising various capabilities of the Red Hat Mobile Application Platform. It consists of two client apps (iOS and Ionic) to show RSS feeds from the internet. The RSS feeds are offered by an API within a Cloud Application on Red Hat Mobile. Since feeds are usually exposed as XML-structured data, the feed is transformed and mobile-optimised by means within RHMAP: e.g. the usage of Node modules and the new API-Mapper capability.

![alt text](./pictures/overview.png "Overview")

![alt text](./pictures/project.png "Project")

## RHMAP-Forms-Submission-Viewer-Demo
This is a [demo project](https://github.com/torbjorndahlen/formsdemo) that uses the `$fh.forms` API to retrieve content submitted through an RHMAP Forms App. It consists of a web app that displays a list of submissions, using `$fh.forms.getSubmissions` from the Cloud App. When selecting a submission the `$fh.forms.getSubmission` is used to retrieve submitted content. The content is examined for the presence of a photo, in which case the `$fh.forms.getSubmissionFile` function is used with the groupId of the photo.

## RHMAP-Chat-Demo
This is a [demo project](https://github.com/torbjorndahlen/kollegornaserver) that uses the $fh.sync API to create a simple chat application.

## RHMAP-BPM-Integration Using Sync
This is a [blog post](http://www.opensourcerers.org/red-hat-map-jboss-bpm-suite-integration-using-sync-framework/) that discuss how to make a mobile app getting regular updates on changes made in tasks and processes in Red Hat JBoss BPM, and how the `$fh.sync` framework can be used together with the [fh-connector-bpm](https://github.com/sebastianfaulhaber/fh-connector-bpm).
This is a simple way of building a process driven, asynchronous mobile app that can be used to push tasks to for example field personnel, call center staff etc.

## RHMAP-Angular-Material-Boilerplate
This is a [demo project](https://github.com/torbjorndahlen/md-boilerplate) that provides a boilerplate for mobile
apps designed with Angular Material Design. The app is responsive to fit different screen sizes.
It consists of modules that can be added or removed from the basic view. The modules include: a toolbar with a
logo that can be replaced, a left sidenav, an analytics panel with a piechart. A choice between a card layout, forms
or a list for the main application screen.
