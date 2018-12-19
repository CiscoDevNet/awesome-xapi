# Awesome xAPI [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![published](https://static.production.devnetcloud.com/codeexchange/assets/images/devnet-published.svg)](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/awesome-xapi)

A curated list of developer resources for [**Webex Room and Desk Devices**](https://www.webex.com/products/devices/index.html) inspired by awesome-go and awesome-python.

> Looking for developer resources for **[Webex Teams](https://www.webex.com/products/teams/)**? check [awesome-webex](https://github.com/CiscoDevNet/awesome-webex).<br/>


### Contributing

Please take a quick gander at the [Contribution guidelines](./CONTRIBUTING.md) first. Thanks to all contributors; you rock!

If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!


### Contents

DISCLAIMER: Cisco does not make any commitments about the resources listed in this document, nor the accuracy of the third party resources and any content accessible via the links below.

- [!Get Started!](#!get-started!)
- [Code samples](#code-samples)
- [Community Articles](#community-articles)
- [Dev Tools](#developer-tools)
- [Reference](#reference)
   - [PDF Guides](#pdf-guides)


## !Get started!

*Tour the xAPI capabilities via step-by-step tutorials.*

* [Introduction to xAPI](https://learninglabs.cisco.com/lab/collab-xapi-intro/step/1) - Learn to invoke your device's API via SSH, HTTP and Node.js (by Cisco DevNet).
* [In-Room Controls](https://learninglabs.cisco.com/lab/collab-xapi-controls/step/1) - Create an "Ultrasound Panel" animated via Node.js or a Macro (by Cisco DevNet).
* [Macro Scripting](https://github.com/ObjectIsAdvantag/xapi-samples/blob/master/macros/pdf/macro-tutorial.pdf) - Write your first Macro scripts (by Cisco CE).
* [Personalizing your device](https://learninglabs.cisco.com/lab/collab-xapi-branding/step/1) - Add your own logo and custom messages from code (by Cisco DevNet).


## Code samples

*Basic samples to end-to-end applications illustrating the xAPI capabilities.*

* HttpFeedback
   * [codec-dashboard](https://github.com/gsheppar/codec-dashboard) - Web dashboard to display/alert on codec information (by gsheppar).
* In-Room Controls
   * [CE9-projects](https://github.com/technologyordie/CE9-projects) - Projects for Cisco DX, MX, SX and Room Systems (by technologyordie).
   * [maze game](https://github.com/ObjectIsAdvantag/xapi-samples/tree/master/controls/maze) - Navigate blind in a maze, look for the treasure (by ObjectIsAdvantag).
* Node.js (jsxapi)
   * [jsxapi](https://github.com/cisco-ce/jsxapi) - JavaScript bindings for Cisco Collaboration Endpoint  XAPI (by Cisco CE).
   * [jsxapi samples](https://github.com/ObjectIsAdvantag/xapi-samples/tree/master/jsxapi) - Example scripts using the Node.js jsxapi (by ObjectIsAdvantag).
* Macros (Javascript)
   * [macros-sample](https://github.com/CiscoDevNet/roomdevices-macros-samples) - Selection of macros proposed by the xAPI dev team (by Cisco CE).
   * [xapi-samples](https://github.com/ObjectIsAdvantag/xapi-samples/tree/master/macros) - Macros to quickly ramp up with the xAPI of your Room Devices (by ObjectIsAdvantag).
* Misc demos
   * [cisco-tp-snapshots](https://github.com/drkchiloll/cisco-tp-snapshots) - Take Snapshots with your Cisco Room Device, aka Telepresence Endpoint (by drkchiloll).
   * [feedback-meeting](https://github.com/tloyau/feedback-meeting) - Dashboard built from feedback collected via a custom "Call Survey" control (by tloyau).
   * [MyRoomKit](https://github.com/CiscoDevNet/botkit-webex-samples/tree/master/roomkit) - Botkit chatbot as an extension of a RoomKit device (by ObjectIsAdvantag).  
   * [roomie](https://bitbucket.org/bjolseth/roomie) - App reporting whether there are people in the meeting rooms (by bjolseth).
   * [roomkit-react-map](https://github.com/ObjectIsAdvantag/roomkit-react-map) - React map showing PeopleCount analytics fired by a set of RoomKits (by ObjectIsAdvantag).
   * [telehealthPresence](https://github.com/voipnorm/telehealthPresence) - Add additional presence states for video endpoints in Jabber (by voipnorm).


## Community Articles

*Blog entries that promote xAPI, cover use cases and propose code samples.*

* [blue-jeans meetings](https://community.bluejeans.com/bluejeans/topics/using-the-cisco-room-system-apis-to-simplify-bluejeans-meetings) - Using the Cisco Room System API's to simplify meetings.
* [cisco developer blog](https://blogs.cisco.com/developer/build-apps-for-webex-devices) - Learn How To Build Applications for Webex Devices. 
* [technology() or die;](http://technologyordie.com/category/collaboration) - Adam Schaeffer sharing projects and ideas.


## Developer Tools

*Handy tools to interact with CE devices.*

* [CiscoTPCustomXML](https://github.com/voipnorm/CiscoTPCustomXML) - Deploy packages to Cisco Telepresence apps (by voipnorm).
* <a name="sandboxes">DevNet Sandboxes</a> - Reserve a CE device and code for up to a week.
   * [CE 9.3](https://devnetsandbox.cisco.com/RM/Diagram/Index/a01c15fc-af6e-497a-92ef-138e06cad308?diagramType=Topology) - RoomKit Sandbox equiped with CE 9.3.
   * [CE 9.6](https://devnetsandbox.cisco.com/RM/Diagram/Index/aada7ed1-18ed-491d-97ad-17ae3a11faba?diagramType=Topology) - RoomKit Sandbox equiped with CE 9.6.
* [Playground](https://controls-editor.herokuapp.com) - Experience the In-Room Controls Editor with no device at hand (by ObjectIsAdvantag).
* [postman-xapi](https://github.com/CiscoDevNet/postman-xapi) - Postman collections for xAPI (by ObjectIsAdvantag).
* [roomkit-collector](https://github.com/ObjectIsAdvantag/roomkit-collector) - Collects PeopleCount from RoomKits and computes weighted averages (by ObjectIsAdvantag).
* [Send-XCommand](https://github.com/unifiedfx/Send-XCommand) - Powershell Cmdlets for sending xConfiguration & xCommand requests (by stephenwelsh).


## Reference

*Documentation, product resources and technical support.*

* Help Articles
    * [Advanced Settings](https://collaborationhelp.cisco.com/article/en-us/n5pqqcm) - Advanced Settings for Room and Desk Devices
    * [Integrating](https://collaborationhelp.cisco.com/article/en-us/n18glho) - In-Room Controls and Use of an External Video Switch with Room Devices
    * [Local user](https://collaborationhelp.cisco.com/article/en-us/jkhs20) - Local User Administration on Room and Desk Devices
    * [Screens Setup Tips](https://collaborationhelp.cisco.com/article/en-us/nyi4lcq) - Recommended external screen settings for Room Devices.
* Reference Portals and Dev Centers
    * [Configuration guides](https://www.cisco.com/c/en/us/support/collaboration-endpoints/telepresence-quick-set-series/products-installation-and-configuration-guides-list.html) - Configure your Touch10 interface or 3rd party Video Switchers
    * [Developer Portal](https://developer.cisco.com/site/roomdevices/) - Technical resources for developers and integrators.
    * [Product resources](https://www.cisco.com/c/en/us/support/collaboration-endpoints/index.html) - Resources for all Supported Collaboration Endpoints.
    * [Project Workplace](https://projectworkplace.cisco.com) - Discover Cisco's devices portfolio, product features and recommandations.
* Technical Support
    * [Forums](https://supportforums.cisco.com/t5/telepresence/bd-p/5886-discussions-telepresence) - Telepresence forum by Cisco Support Community.
    * ['xAPI devs' space](https://eurl.io/#rkp76XDrG) - Chat live in Webex Teams with other developers.
* Troubleshooting
    * [CE Release notes](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/software/ce9/release-notes/ce-software-release-notes-ce9.pdf) - New features and functionality in CE9.
    * [Known issues](https://collaborationhelp.cisco.com/article/en-us/yurdv2) - Known and Resolved issues for Cloud-registered Room and Desk devices.
    * [What's new](https://collaborationhelp.cisco.com/article/en-us/DOC-10372) - New features and capabilities for Cloud-registered Room devices.
* Videos
    * [Presenter Track](https://www.youtube.com/watch?v=-MKlCT1xupM) - Demonstrate how PresenterTrack behaves in a few common scenarios.
* 3rd-party Control Systems
    * [AMX/Harman](https://trade.amx.com/Net/Inconcert/Devices/inconcertmainpage.aspx)
    * [Creston](http://applicationmarket.crestron.com/cisco/)
    * [Extron](https://www.extron.com/company/article.aspx?id=ciscotouch)


### PDF Guides

*Administration guides, and API Reference for xConfiguration, xCommand, xStatus.*

* CE 9.5
    * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce95/collaboration-endpoint-software-api-reference-guide-ce95.pdf)
* CE 9.4
    * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce94/collaboration-endpoint-software-api-reference-guide-ce94.pdf)
    * [Customization Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce94/sx-mx-dx-room-kit-customization-guide-ce94.pdf)
* CE 9.3
    * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce93/collaboration-endpoint-software-api-reference-guide-ce93.pdf)
    * [Customization Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce93/sx-mx-dx-room-kit-customization-guide-ce93.pdf)
* CE 9.2
    * [Administration Guide (RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce92/room-kit-administrator-guide-ce92.pdf)
    * [API Reference Guide (DX70/DX80)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce92/dx70-dx80-api-reference-guide-ce92.pdf)
    * [API Reference Guide (RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce92/room-kit-api-reference-guide-ce92.pdf)
    * [Customization Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce92/sx-mx-dx-room-kit-customization-guide-ce92.pdf)
