# Contribute to Freq51

Freq51 is built by the community. You can help improve the mesh and this documentation.

## Share a Build or Coverage Result

Useful submissions include:

- A hardware build with photos, parts, and lessons learned
- Site-survey or coverage images
- Corrections to infrastructure details
- A new or updated node entry
- A member project, tool, or integration

## What to Include

- A clear node or project name
- Region and general area
- Hardware, antenna, power, and firmware details
- Images or links you are allowed to share
- Whether the information is current, planned, or unverified

Start by posting the details in [Freq51 Discord](https://discord.gg/qmeeRPkq3g). The community can help verify the information before it is added to the site.

## Help With Maps and Network Stats

You can help improve Freq51 maps and network statistics by hosting an MQTT feeder. A feeder is a node that listens to the mesh and securely shares the packets it hears with Freq51’s map and statistics services over the internet.

### What It Helps With

- Makes local mesh activity more visible on community maps.
- Gives network statistics a clearer view of active nodes and their activity.
- Helps show where the mesh is being heard, which can support coverage planning and troubleshooting.

### What You Need

- A node that is already connected to the Freq51 mesh.
- Reliable internet access for that node.
- A location where the node can remain online consistently.

### Common Feeder Hardware

Many types of Meshtastic hardware can be used as a feeder when they have a dependable internet connection. Common examples include:

- An ESP32-based node using Wi-Fi.
- A Linux-based node using a LoRa HAT or USB-connected radio.
- A RAK-based node with an Ethernet module.

The best choice depends on the equipment and connection available at the site. We can help determine whether an existing node is a good fit before any changes are made.

A feeder reports what it hears; it does not replace RF coverage, extend radio range, or send internet traffic back onto the mesh. We coordinate feeder setup with each operator so it supports the network cleanly. If you are interested, reach out in [Freq51 Discord](https://discord.gg/qmeeRPkq3g) and we will help you get set up.

*Last edited: August 18, 2026*
