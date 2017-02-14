# RHMAP-Demo-Apps
## RHMAP-RSS-Reader-Demo
This is a [demo project](https://github.com/mmetting/RHMAP-RSS-Reader-Demo) utilising various capabilities of the Red Hat Mobile Application Platform. It consists of two client apps (iOS and Ionic) to show RSS feeds from the internet. The RSS feeds are offered by an API within a Cloud Application on Red Hat Mobile. Since feeds are usually exposed as XML-structured data, the feed is transformed and mobile-optimised by means within RHMAP: e.g. the usage of Node modules and the new API-Mapper capability.

![alt text](./pictures/overview.png "Overview")

## Agile Development & DevOps

1. Create new project
2. Mock data from server side
3. Iteratively prototype and implement client (Ionic – Cordova app)
4. Import / Onboard existing app (native iOS – Swift app)
5. Create a connector to backend system
6. Transform data from backend system, make this a reusable service
7. Replace mock data with backend data