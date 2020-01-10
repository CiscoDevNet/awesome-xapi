# Awesome xAPI [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![published](https://static.production.devnetcloud.com/codeexchange/assets/images/devnet-published.svg)](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/awesome-xapi)

A curated list of developer resources for [**Webex Room and Desk Devices**](https://www.webex.com/products/devices/index.html) inspired by awesome-go and awesome-python.

> Looking for developer resources for **[Webex Teams](https://www.webex.com/products/teams/)**? check [awesome-webex](https://github.com/CiscoDevNet/awesome-webex).<br/>


### Contributing

Please take a quick gander at the [Contribution guidelines](./CONTRIBUTING.md) first. Thanks to all contributors; you rock!

If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!


### Contents

DISCLAIMER: Cisco does not make any commitments about the resources listed in this document, nor the accuracy of the third party resources and any content accessible via the links below.

* [!Get Started!](#!get-started!)
* [Articles and Blogs](#articles)
* [Building Blocks](#building-blocks)
* [Code samples](#code-samples)
* [Developer Tools](#developer-tools)
   * [DevNet Sandbox](#sandbox)
* [Reference](#reference)
   * [PDF Guides](#reference-guides)
* [3rd Party Hardware](#third-party)


## !Get started!

*Tour the xAPI via step-by-step tutorials.*

* [Introduction to xAPI](https://learninglabs.cisco.com/lab/collab-xapi-intro/step/1) - Learn to invoke your device's API via SSH, HTTP and Node.js (by Cisco DevNet).
* [In-Room Controls](https://learninglabs.cisco.com/lab/collab-xapi-controls/step/1) - Create an "Ultrasound Panel" animated via Node.js or a Macro (by Cisco DevNet).
* [Macro Scripting](https://github.com/CiscoDevNet/xapi-samples/blob/master/macros/pdf/macro-tutorial.pdf) - Write your first Macro scripts (by Cisco CE).
* [Personalizing your device](https://learninglabs.cisco.com/lab/collab-xapi-branding/step/1) - Add your own logo and custom messages from code (by Cisco DevNet).


## Articles

*Blogs and community articles that document features, cover use cases or propose code samples.*

* Blogs introducting new Features
   * [Introducing HTTPClient](https://community.cisco.com/t5/collaboration-voice-and-video/ce9-6-x-in-room-control-and-macros-usb-input-devices-http-post/ba-p/3765081) - HTTP POST/PUT/GET/DELETE/PATCH with return
   * [Introducing Kiosk Mode](https://community.cisco.com/t5/collaboration-voice-and-video/ce9-6-x-in-room-control-and-macros-usb-input-devices-http-post/ba-p/3765081) - Hide default Call, Share and Meetings buttons
   * [Introducing USB input](https://community.cisco.com/t5/collaboration-voice-and-video/ce9-6-x-in-room-control-and-macros-usb-input-devices-http-post/ba-p/3765081) - Support for 3rd party USB input devices (keyboards)
   * [Introducing WebSockets](https://community.cisco.com/t5/collaboration-voice-and-video/xapi-over-websocket-xows-ce9-7-x/ba-p/3831553) - xAPI over WebSockets: XoWS (pronounced cows).
   * [Introducing WebEngine](https://community.cisco.com/t5/collaboration-voice-and-video/a-dive-into-web-engine-and-the-new-ui-extensions-editor-digital/ba-p/3947191) - A dive into Web Engine, Digital Signage & Web Apps.
* Community Articles
   * [CE Programmability](https://blogs.cisco.com/developer/build-apps-for-webex-devices) - Learn How To Build Applications for Webex Devices.
   * [Holy cows!](https://blog.webex.com/collaboration-devices/holy-cows-xows-delivering-the-art-of-possible-with-video-devices/) - Delivering the art of possible with video devices.
   * [SIP messaging channel](https://voipnorm.blogspot.com/2019/07/ce-sip-messaging-channel-for-remote.html) - SIP Messaging Channel for Remote Endpoint Control.
   * [technology() or die;](http://technologyordie.com/category/collaboration) - Adam Schaeffer sharing projects and ideas.
   * [WebSocket vs SSH vs HttpFeedback](http://voipnorm.blogspot.com/2019/07/ce-websocket-v-ssh-v-httpfeedback-which.html) - Which is Best?.
* Help Articles
   * [Advanced Settings](https://collaborationhelp.cisco.com/article/en-us/n5pqqcm) - Advanced Settings for Room and Desk Devices
   * [Integrating](https://collaborationhelp.cisco.com/article/en-us/n18glho) - In-Room Controls and Use of an External Video Switch with Room Devices
   * [Local user](https://collaborationhelp.cisco.com/article/en-us/jkhs20) - Local User Administration on Room and Desk Devices
   * [Screens setup tips](https://collaborationhelp.cisco.com/article/en-us/nyi4lcq) - Recommended external screen settings for Room Devices.
   * [USB input-device](https://help.webex.com/en-us/nhqh1mf/Example-on-the-Use-of-a-Third-Party-USB-Input-Device) - Use of a 3rd party USB input device.


## Building Blocks

*Helper libraries to interact with codecs*

* Command Line Interface
   * [xows CLI](https://github.com/cisco-ce/pyxows/blob/master/xows/__main__.py) - Command-line utility built on top of pyxows (by Cisco CE).
* JavaScript
   * [jsxapi](https://github.com/cisco-ce/jsxapi) - JavaScript bindings for Cisco Collaboration Endpoint  XAPI (by Cisco CE).
   * [sugar](https://github.com/valgaze/sugar) - Syntactic "$ugar" for handling user input (by valgaze).
* Postman
   * [postman-xapi](https://github.com/CiscoDevNet/postman-xapi) - Postman collections for xAPI (by ObjectIsAdvantag).
* PowerShell
   * [Send-XCommand](https://github.com/unifiedfx/Send-XCommand) - Cmdlets for sending xConfiguration & xCommand requests (by stephenwelsh).
* Python
   * [pyxows](https://github.com/cisco-ce/pyxows) - Python bindings for Cisco Collaboration Endpoint xAPI over WebSockets (by Cisco CE).


## Code samples

*From basic examples to finalized solutions illustrating the xAPI capabilities.*

* Repositories of examples
   * [CE9-projects](https://github.com/technologyordie/CE9-projects) - Projects for Cisco DX, MX, SX and Room Systems (by technologyordie).
   * [macros-sample](https://github.com/CiscoDevNet/roomdevices-macros-samples) - Selection of macros proposed by the xAPI dev team (by Cisco CE).
   * [xapi-samples](https://github.com/CiscoDevNet/xapi-samples) - UI extensions, macros and scripts to quickly ramp up (by ObjectIsAdvantag).
   * [yolo-oslo](https://github.com/acaeti/yolo-oslo) - Repository of in-room controls and macro samples (by acaeti).
* Solutions
   * [cisco-tp-snapshots](https://github.com/drkchiloll/cisco-tp-snapshots) - Take snapshots with your Cisco Room Device, aka Telepresence Endpoint (by drkchiloll).
   * [codec-dashboard](https://github.com/gsheppar/codec-dashboard) - Web dashboard to display/alert on codec information (by gsheppar).
   * [feedback-meeting](https://github.com/tloyau/feedback-meeting) - Dashboard built from feedback collected via a custom "Call Survey" control (by tloyau).
   * [maze game](https://github.com/CiscoDevNet/xapi-samples/tree/master/controls/maze) - Navigate blind in a maze, look for the treasure (by ObjectIsAdvantag).
   * [MyRoomKit](https://github.com/CiscoDevNet/botkit-webex-samples/tree/master/roomkit) - Botkit chatbot as an extension of a RoomKit device (by ObjectIsAdvantag).  
   * [roomie](https://bitbucket.org/bjolseth/roomie) - App reporting whether there are people in the meeting rooms (by bjolseth).
   * [roomkit-collector](https://github.com/ObjectIsAdvantag/roomkit-collector) - Collect PeopleCount events and compute weighted averages (by ObjectIsAdvantag).
   * [roomkit-react-map](https://github.com/ObjectIsAdvantag/roomkit-react-map) - React map showing PeopleCount analytics fired by a set of RoomKits (by ObjectIsAdvantag).
   * [telehealthPresence](https://github.com/voipnorm/telehealthPresence) - Add additional presence states for video endpoints in Jabber (by voipnorm).
   * [video status monitor](https://github.com/DJF3/Cisco-Video-System-Status-Monitor) - Web page displaying call status and people count/presence (by DJF3).


## Developer Tools

*Handy tools to build, test and deploy applications.*

* <a name="sandbox">Sandbox</a><a name="sandboxes"></a> - Reserve a CE device and code for up to a week (by DevNet).
   * [CE 9.9 Sandbox](https://devnetsandbox.cisco.com/RM/Diagram/Index/a01c15fc-af6e-497a-92ef-138e06cad308?diagramType=Topology) - RoomKit Sandbox equiped with CE 9.9.
   * [CE 9.7 Sandbox](https://devnetsandbox.cisco.com/RM/Diagram/Index/aada7ed1-18ed-491d-97ad-17ae3a11faba?diagramType=Topology) - RoomKit Sandbox equiped with CE 9.7.
* Test
   * [Playground](https://controls-editor.herokuapp.com) - Launch the UI Extensions Editor straight from Chrome, no codec (by ObjectIsAdvantag).
   * SIP test addresses - 111@bjn.vc, fireplace@ivr.vc, goldfish@selfie.vc, halloween@ivr.vc, havnen@expressway.dk.
* Deploy
   * [CE-Deploy](https://github.com/voipnorm/CE-Deploy) - Desktop application for deploying features (by voipnorm).
   * [CiscoTPCustomXML](https://github.com/voipnorm/CiscoTPCustomXML) - Deploy packages to Cisco Telepresence apps (by vipnorm).


## Reference

*Documentation, product resources and technical support.*

* Portals and Dev Centers
   * [Adoption Toolkits](https://community.cisco.com/t5/collaboration-adoption-documents/cisco-webex-devices-adoption-toolkits/ta-p/3832348) - Video value statements, quick-start guides, use cases and promotional posters.
   * [Configuration guides](https://www.cisco.com/c/en/us/support/collaboration-endpoints/telepresence-quick-set-series/products-installation-and-configuration-guides-list.html) - Configure your Touch10 interface or 3rd party Video Switchers
   * [Developer Portal](https://developer.cisco.com/site/roomdevices/) - Technical resources for developers and integrators.
   * [Product resources](https://www.cisco.com/c/en/us/support/collaboration-endpoints/index.html) - Resources for all Supported Collaboration Endpoints.
   * [Project Workplace](https://projectworkplace.cisco.com) - Discover Cisco's devices portfolio, product features and recommandations.
* Release notes
   * [CE 9.x Release notes](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/software/ce9/release-notes/ce-software-release-notes-ce9.pdf) - New features and functionality in CE9.
   * [RoomOS What's new](https://help.webex.com/en-us/6ger7db/What-s-New-in-RoomOS) - New features and capabilities for RoomOS.
* Technical Support
   * ['xAPI devs' space](https://eurl.io/#rkp76XDrG) - Chat live with other developers in Webex Teams.
   * [Forums](https://supportforums.cisco.com/t5/telepresence/bd-p/5886-discussions-telepresence) - Telepresence forum by Cisco Support Community.
   * [Known issues](https://help.webex.com/en-us/llygcp/Known-and-Resolved-Issues-in-RoomOS) - Known and Resolved issues for RoomOS.   
* Videos
   * [Customizing Devices](https://www.youtube.com/watch?v=h9Hv829SM14&list=PL_YnWo4XhzTe8CyOppyhheB8UN40mDYiX) - Introduction to Video Series.
   * [Kiosk](https://www.youtube.com/watch?v=zn9gDuPwyrY) - Removing default buttons.
   * [Presenter Track](https://www.youtube.com/watch?v=-MKlCT1xupM) - How PresenterTrack behaves in a few common scenarios.
   * [Timer](https://www.youtube.com/watch?v=YNN9rFbT6bk) - Timer creation for Webex devices.
   * [UI Extensions](https://www.youtube.com/watch?v=kEXjGpMdVaU&list=PL_YnWo4XhzTe8CyOppyhheB8UN40mDYiX&index=3) - Creating a speed dial.
   * [Web Apps](https://www.youtube.com/watch?v=qKqlIReRJog&t=6s) - Creating Web Applications on a Webex Board.


### Reference Guides

*API Reference, Configuration and Administration guide for specific versions of CE and RoomOS.*

* CE 9.10
   * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce910/collaboration-endpoint-software-api-reference-guide-ce910.pdf),[Administrator Guide (CodecPro)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce910/codec-pro-administrator-guide-ce910.pdf), and [(RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce910/room-kit-administrator-guide-ce910.pdf), Customization Guide (coming)
* CE 9.9
   * [Blog: WebEngine and new UI Extensions Editor](https://community.cisco.com/t5/collaboration-voice-and-video/a-dive-into-web-engine-and-the-new-ui-extensions-editor-digital/ba-p/3947191)
   * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce99/collaboration-endpoint-software-api-reference-guide-ce99.pdf), [Administrator Guide (CodecPro)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce99/codec-pro-administrator-guide-ce99.pdf), and [(RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce99/room-kit-administrator-guide-ce99.pdf), [Customization Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce99/sx-mx-dx-room-kit-boards-customization-guide-ce99.pdf)
* CE 9.8
   * [Blog: New features](https://community.cisco.com/t5/collaboration-voice-and-video/ce9-6-x-in-room-control-and-macros-usb-input-devices-http-post/ba-p/3765081), 
   * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce98/collaboration-endpoint-software-api-reference-guide-ce98.pdf), [Administrator Guide (CodecPro)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce98/codec-pro-administrator-guide-ce98.pdf), and [(RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce98/room-kit-administrator-guide-ce98.pdf), [Customization Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce98/sx-mx-dx-room-kit-boards-customization-guide-ce98.pdf)
* CE 9.7
   * [Blog: xAPI over WebSocket](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/api/collaboration-endpoint-software-api-transport.pdf)
   * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce97/collaboration-endpoint-software-api-reference-guide-ce97.pdf), [Administrator Guide (CodecPro)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce97/codec-pro-administrator-guide-ce97.pdf), and [(RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce97/room-kit-administrator-guide-ce97.pdf), [Customization Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce97/sx-mx-dx-room-kit-customization-guide-ce97.pdf)
* CE 9.6
   * [Blog: New features](https://community.cisco.com/t5/collaboration-voice-and-video/ce9-6-x-in-room-control-and-macros-usb-input-devices-http-post/ba-p/3765081)
   * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce96/collaboration-endpoint-software-api-reference-guide-ce96.pdf), [Administrator Guide (CodecPro)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce96/codec-pro-administrator-guide-ce96.pdf), and [(RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce96/room-kit-administrator-guide-ce96.pdf), [Customization Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce96/sx-mx-dx-room-kit-customization-guide-ce96.pdf)
* CE 9.5
   * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce95/collaboration-endpoint-software-api-reference-guide-ce95.pdf), [Administrator Guide (CodecPro)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce95/codec-pro-administrator-guide-ce95.pdf), and [(RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce95/room-kit-administrator-guide-ce95.pdf), [Customization Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce95/sx-mx-dx-room-kit-customization-guide-ce95.pdf)
* CE 9.4
   * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce94/collaboration-endpoint-software-api-reference-guide-ce94.pdf), [Administrator Guide (CodecPro)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce94/codec-pro-administrator-guide-ce94.pdf), and [(RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce94/room-kit-administrator-guide-ce94.pdf), [Customization Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce94/sx-mx-dx-room-kit-customization-guide-ce94.pdf)
* CE 9.3
   * [API Reference Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce93/collaboration-endpoint-software-api-reference-guide-ce93.pdf), [Administration Guide (RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce93/room-kit-administrator-guide-ce93.pdf), [Customization Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce93/sx-mx-dx-room-kit-customization-guide-ce93.pdf)
* CE 9.2
   * [API Reference Guide (DX70/DX80)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce92/dx70-dx80-api-reference-guide-ce92.pdf) and [(RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce92/room-kit-api-reference-guide-ce92.pdf), [Administration Guide (RoomKit)](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce92/room-kit-administrator-guide-ce92.pdf), [Customization Guide](https://www.cisco.com/c/dam/en/us/td/docs/telepresence/endpoint/ce92/sx-mx-dx-room-kit-customization-guide-ce92.pdf)


## Third-Party

*Hardware, integrations and control systems*

* Control Systems
   * [AMX/Harman](https://trade.amx.com/Net/Inconcert/Devices/inconcertmainpage.aspx)
   * [Creston](http://applicationmarket.crestron.com/cisco/)
   * [Extron](https://www.extron.com/company/article.aspx?id=ciscotouch)
   * [Lightware](https://lightware.com/cisco-integration-tool/)
* Other Hardware
   * [Audio Plug Terminal Block](https://www.adafruit.com/product/2914)
   * [USB to Serial Adapter](https://www.tripplite.com/support/USA19HS)
* USB HID Compliant devices
   * [Dynamag](https://www.magtek.com/product/dynamag) - Card Reader
   * [Logitech R400](https://support.logi.com/hc/en-us/articles/360023466513-R400-Technical-Specifications) - Wireless Presenter
* Video Integrations
   * [Kaptivo](https://kaptivo.com/cisco-rooms/)
