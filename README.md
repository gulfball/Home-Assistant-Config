<p><h1 align="center">My home Assistant Configuration</h1>
<h3 align="center">Offered to you by Maxi1134</h3>
</p>
<br>

### Preamble;
This whole ~mess~ adventure started in 2018. When I lost my keys twice... in a week.  
This, forcing my former roommatte to come to my rescue, lead him to buy a [Schlage Zwave Lock](https://www.schlage.com/en/home/smart-locks/connect-zwave.html) coupled with a [Samsung SmartThings hub(2018 version)](https://www.amazon.ca/Samsung-SmartThings-Smart-Home-Hub/dp/B010NZV0GE).  
  
Once that was acquired, there was no going back; The hub was quickly linked to Home-Assistant along some Xiaomi sensor using custom zigbee integrations for the hub.  Unfortunately, this quickly proved to be limiting. I was at this stage using 2 hubs ( Samsung and Phillips) and needed some streamlining.  
  
I eventually ended up moving all my Zigbee and Zwave devices to a [HUSBZB-1 stick](https://www.amazon.ca/-/fr/QuickStick-Combo-HUSBZB-1-Nortek-Cert/dp/B0157GOEA8/ref=sr_1_5?__mk_fr_CA=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=2JP8XY8SQ0LKQ&keywords=nortek&qid=1676432194&s=hi&sprefix=nortek%2Ctools%2C79&sr=1-5) coupled with [ZHA](https://www.home-assistant.io/integrations/zha/) which proved to be a very good decision, no more Zigbee drops or Zwave issues coming from the use of the SmartThings hub.

Eventually followed a [second server for storage and a nas for backups](documentation/hardware.md), more devices [(Now over a hundred!)](documentation/zigbee.md) and lots and lots of automations!  
This takes us to 2023, where I decided to share my 5 years of work as to help people with their own installation!

And of course, do not hesitate to open up an issue if you have any specific question on the YAML code I made.

### A Few Screenshots;

<h5 align="center">Wall Displays</h5>
<p align="middle">
  <img src="/assets/Tablet_A8/musicdemo.gif" width="43%" />
  <img src="/assets/Tablet_S7FE/framed_light_panel_lowres.gif" width="38%" />
</p>

<h5 align="center">Some Node-Red automations</h5>
<p align="middle">
  <img src="/assets/node-red/example_flow_microwave.png" width="90%" />
  <img src="/assets/node-red/example_flow.png" width="90%" />
  <img src="/assets/node-red/example_flow_2.png" width="90%" />
</p>


### Links:

<a href="documentation/hardware.md"><img src="https://img.shields.io/badge/Hardware%20Specifications-purple" alt="This is what runs everything"></a> <br>
<a href="documentation/zigbee.md"><img src="https://img.shields.io/badge/Zigbee%20Devices-green" alt="This is what runs everything"></a> <br>

<br>
<a href=".storage/"><img src="https://img.shields.io/badge/Lovelace%20Interfaces-orange" alt="Actually my .storage folder, but eh!"></a> <br>
<a href=".storage/"><img src="https://img.shields.io/badge/Nodered%20Flows-red" alt="Read the README!"></a> <br>
 <br>
<br>
<a href="/documentation/indoor_localization.md"><img src="https://img.shields.io/badge/Indoor%20Localization-blue" alt="They know where you are..."></a> <br>