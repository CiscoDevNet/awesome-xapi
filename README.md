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
   * [video status monitor](https://github.com/DJF3/Cisco-Video-System-Status-Monitor) - Web page displaying call status and people count/presence (by DJF3).
* Python (pyxows)
   * [pyxows](https://github.com/cisco-ce/pyxows) - Python bindings for Cisco Collaboration Endpoint xAPI over WebSockets (by Cisco CE).


## Community Articles

*Blog entries that promote xAPI, cover use cases and propose code samples.*

* [cisco developer blog](https://blogs.cisco.com/developer/build-apps-for-webex-devices) - Learn How To Build Applications for Webex Devices. 
* [technology() or die;](http://technologyordie.com/category/collaboration) - Adam Schaeffer sharing projects and ideas.
* [xAPI over WebSockets](https://community.cisco.com/t5/collaboration-voice-and-video/xapi-over-websocket-xows-ce9-7-x/ba-p/3831553) - Introducing XoWS (pronounced cows) by Magnus Ohm.


## Developer Tools

*Handy tools to interact with CE devices.*

* [CiscoTPCustomXML](https://github.com/voipnorm/CiscoTPCustomXML) - Deploy packages to Cisco Telepresence apps (by voipnorm).
* [CLI](https://github.com/cisco-ce/pyxows/blob/master/xows/__main__.py) - Command-line utility built on top of pyxows (by Cisco CE).
* [Playground](https://controls-editor.herokuapp.com) - Experience the In-Room Controls Editor with no device at hand (by ObjectIsAdvantag).
* [postman-xapi](https://github.com/CiscoDevNet/postman-xapi) - Postman collections for xAPI (by ObjectIsAdvantag).
* [roomkit-collector](https://github.com/ObjectIsAdvantag/roomkit-collector) - Collects PeopleCount from RoomKits and computes weighted averages (by ObjectIsAdvantag).
* [Send-XCommand](https://github.com/unifiedfx/Send-XCommand) - Powershell Cmdlets for sending xConfiguration & xCommand requests (by stephenwelsh).
* SIP for testing
    * 111@bjn.vc
    * fireplace@ivr.vc
    * goldfish@selfie.vc
    * halloween@ivr.vc
    * havnen@expressway.dk


## Reference

*Documentation, product resources and technical support.*

* Help Articles
    * [Advanced Settings](https://collaborationhelp.cisco.com/article/en-us/n5pqqcm) - Advanced Settings for Room and Desk Devices
    * [Integrating](https://collaborationhelp.cisco.com/article/en-us/n18glho) - In-Room Controls and Use of an External Video Switch with Room Devices
    * [Local user](https://collaborationhelp.cisco.com/article/en-us/jkhs20) - Local User Administration on Room and Desk Devices
    * [Screens setup tips](https://collaborationhelp.cisco.com/article/en-us/nyi4lcq) - Recommended external screen settings for Room Devices.
    * [USB input-device](https://help.webex.com/en-us/nhqh1mf/Example-on-the-Use-of-a-Third-Party-USB-Input-Device) - Use of a 3rd party USB input device.
    * [xAPI over WebSocket](https://community.cisco.com/t5/collaboration-voice-and-video/xapi-over-websocket-xows-ce9-7-x/ba-p/3831553) - xAPI over WebSocket article on Cisco Community site.
* Reference Portals and Dev Centers
    * [Configuration guides](https://www.cisco.com/c/en/us/support/collaboration-endpoints/telepresence-quick-set-series/products-installation-and-configuration-guides-list.html) - Configure your Touch10 interface or 3rd party Video Switchers
    * [Developer Portal](https://developer.cisco.com/site/roomdevices/) - Technical resources for developers and integrators.
    * [Product resources](https://www.cisco.com/c/en/us/support/collaboration-endpoints/index.html) - Resources for all Supported Collaboration Endpoints.
    * [Project Workplace](https://projectworkplace.cisco.com) - Discover Cisco's devices portfolio, product features and recommandations.
* <a name="sandboxes">Sandboxes</a> - Reserve a CE device and code   for up to a week (by DevNet)
    * [CE 9.7](https://devnetsandbox.cisco.com/RM/Diagram/Index/aada7ed1-18ed-491d-97ad-17ae3a11faba?diagramType=Topology) - RoomKit Sandbox equiped with CE 9.7.1
    * [CE 9.9](https://devnetsandbox.cisco.com/RM/Diagram/Index/a01c15fc-af6e-497a-92ef-138e06cad308?diagramType=Topology) - RoomKit Sandbox equiped with CE 9.9.
* Technical Support
    * [Forums](https://supportforums.cisco.com/t5/telepresence/bd-p/5886-discussions-telepresence) - Telepresence forum by Cisco Support Community.
    * ['xAPI devs' space](https://eurl.io/#rkp76XDrG) - Chat live in Webex Teams with other developers.
* Troubleshooting
    * [CE Release notes](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/software/ce9/release-notes/ce-software-release-notes-ce9.pdf) - New features and functionality in CE9.
    * [Known issues](https://help.webex.com/en-us/llygcp/Known-and-Resolved-Issues-in-RoomOS) - Known and Resolved issues for RoomOS.
    * [What's new](https://help.webex.com/en-us/6ger7db/What-s-New-in-RoomOS) - New features and capabilities for RoomOS.
* Videos
    * [Presenter Track](https://www.youtube.com/watch?v=-MKlCT1xupM) - Demonstrate how PresenterTrack behaves in a few common scenarios.
* 3rd-party Control Systems
    * [AMX/Harman](https://trade.amx.com/Net/Inconcert/Devices/inconcertmainpage.aspx)
    * [Creston](http://applicationmarket.crestron.com/cisco/)
    * [Extron](https://www.extron.com/company/article.aspx?id=ciscotouch)
    * [Lightware](https://lightware.com/cisco-integration-tool/)


### PDF Guides

*Administration guides, and API Reference for xConfiguration, xCommand, xStatus.*

* [CE 9.x Release notes](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/software/ce9/release-notes/ce-software-release-notes-ce9.pdf)
* CE 9.9
    * [Administrator Guide (CodecPro)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce99/codec-pro-administrator-guide-ce99.pdf)
    * [Administrator Guide (RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce99/room-kit-administrator-guide-ce99.pdf)
    * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce99/collaboration-endpoint-software-api-reference-guide-ce99.pdf)
* CE 9.8
    * [Administrator Guide (CodecPro)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce98/codec-pro-administrator-guide-ce98.pdf)
    * [Administrator Guide (RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce98/room-kit-administrator-guide-ce98.pdf)
    * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce98/collaboration-endpoint-software-api-reference-guide-ce98.pdf)
* CE 9.7
    * [Administrator Guide (CodecPro)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce97/codec-pro-administrator-guide-ce97.pdf)
    * [Administrator Guide (RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce97/room-kit-administrator-guide-ce97.pdf)
    * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce97/collaboration-endpoint-software-api-reference-guide-ce97.pdf) - xConfiguration, xCommand, xStatus documentation.
    * [xAPI over WebSocket](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/api/collaboration-endpoint-software-api-transport.pdf) - Amendment to connect to and use the API over WebSocket.
* CE 9.6
    * [Administrator Guide (CodecPro)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce96/codec-pro-administrator-guide-ce96.pdf)
    * [Administrator Guide (RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce96/room-kit-administrator-guide-ce96.pdf)
    * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce96/collaboration-endpoint-software-api-reference-guide-ce96.pdf) - xConfiguration, xCommand, xStatus documentation.
    * [New features](https://community.cisco.com/t5/collaboration-voice-and-video/ce9-6-x-in-room-control-and-macros-usb-input-devices-http-post/ba-p/3765081) - USB input devices, HTTP POST/PUT, hiding default UI buttons.
* CE 9.5
    * [Administrator Guide (CodecPro)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce95/codec-pro-administrator-guide-ce95.pdf)
    * [Administrator Guide (RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce95/room-kit-administrator-guide-ce95.pdf)
    * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce95/collaboration-endpoint-software-api-reference-guide-ce95.pdf)
* CE 9.4
    * [Administrator Guide (CodecPro)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce94/codec-pro-administrator-guide-ce94.pdf)
    * [Administrator Guide (RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce94/room-kit-administrator-guide-ce94.pdf)
    * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce94/collaboration-endpoint-software-api-reference-guide-ce94.pdf)
    * [Customization Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce94/sx-mx-dx-room-kit-customization-guide-ce94.pdf)
* CE 9.3
    * [Administration Guide (RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce93/room-kit-administrator-guide-ce93.pdf)
    * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce93/collaboration-endpoint-software-api-reference-guide-ce93.pdf)
    * [Customization Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce93/sx-mx-dx-room-kit-customization-guide-ce93.pdf)
* CE 9.2
    * [Administration Guide (RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce92/room-kit-administrator-guide-ce92.pdf)
    * [API Reference Guide (DX70/DX80)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce92/dx70-dx80-api-reference-guide-ce92.pdf)
    * [API Reference Guide (RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce92/room-kit-api-reference-guide-ce92.pdf)
    * [Customization Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce92/sx-mx-dx-room-kit-customization-guide-ce92.pdf)
