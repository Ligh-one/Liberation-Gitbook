# 🟧 Connecting to an Artnet node

In Liberation, Art-Net input enables external DMX controllers to influence laser output, integrating seamlessly with lighting setups.

{% hint style="info" %}
What is Art-Net?&#x20;

Art-Net is a network protocol for sending DMX data over Ethernet, originally developed by Artistic Licence in 1998. Unlike traditional DMX, which is limited to 512 channels per universe, Art-Net supports up to 32,768 universes—enough for over 16 million channels!&#x20;

**Nerd facts!**

Early versions relied on broadcasting, but modern Art-Net can use unicast, reducing network traffic. It’s lightweight, UDP-based (so no error correction, but super fast), and even supports automatic node discovery. While mostly used for lighting, Art-Net is also found in lasers, kinetic installations, and even fountain shows.

Fun fact: Art-Net 4 introduced ArtSync, helping keep multiple universes in perfect sync for flicker-free effects!&#x20;
{% endhint %}

