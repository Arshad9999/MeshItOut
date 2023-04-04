<link rel="stylesheet" href="style/style.css">
<div class="notification-menu" link rel="stylesheet" href="style/style.css">
  <div align="center">
      <a href="../README.md">Home</a>&nbsp;&nbsp;&nbsp;<a href="../Demo">Demo</a>&nbsp;&nbsp;&nbsp;<a href="../about-kavach" text-align: center>About</a>
  </div>
</div>
</link>

<div align="center"><b><h2>For developing a system that can detect apps like fire chat that uses Mesh network to connect user over wifi and Bluetooth here are few things that one have to consider first:</h2></b></div>

---

<div align="center"><b><h3>how communication is done over wifi and bluetooth</h3></b></div>

---

WiFi and Bluetooth are two wireless communication technologies that enable devices to communicate with each other without the need for physical cables. While both technologies enable wireless communication, they operate in different ways.
WiFi operates over a wireless network using radio waves to transmit data. The device sends data to the router, which then broadcasts the data over the wireless network. The receiving device picks up the signal and decodes it to retrieve the data. WiFi can transmit data at higher speeds than Bluetooth, making it suitable for applications such as streaming video, downloading large files, and browsing the internet.
Bluetooth, on the other hand, is a short-range wireless communication technology that operates over radio waves in the 2.4 GHz frequency range. Bluetooth devices connect to each other using a process called pairing, which involves exchanging security codes to establish a secure connection. Once the connection is established, the devices can exchange data such as files, music, and other types of media. Bluetooth is suitable for low-power, short-range communication, such as connecting a smartphone to a wireless speaker or headphones.
In summary, WiFi and Bluetooth are two wireless communication technologies that enable devices to communicate with each other wirelessly, but they operate in different ways and are suitable for different applications. WiFi is designed for high-speed, long-range communication, while Bluetooth is designed for low-power, short-range communication.

---

The thing is that <a href="https://en.wikipedia.org/wiki/Wi-Fi_6">Wi-Fi communication</a> can be done over all these frequencies:

<table>
  <thead>
    <tr>
      <th>Generation</th>
      <th>IEEE standard</th>
      <th>Adopted</th>
      <th>Maximum link rate (Mbit/s)</th>
      <th>Radio frequency (GHz)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Wi-Fi 7</td>
      <td>802.11be</td>
      <td>2024</td>
      <td>1376 to 46120</td>
      <td>2.4/5/6</td>
    </tr>
    <tr>
      <td>Wi-Fi 6E</td>
      <td>802.11ax</td>
      <td>2020</td>
      <td>574 to 9608</td>
      <td>6</td>
    </tr>
    <tr>
      <td>Wi-Fi 6</td>
      <td>802.11ax</td>
      <td>2019</td>
      <td>574 to 9608</td>
      <td>2.4/5</td>
    </tr>
    <tr>
      <td>Wi-Fi 5</td>
      <td>802.11ac</td>
      <td>2014</td>
      <td>433 to 6933</td>
      <td>5</td>
    </tr>
    <tr>
      <td>Wi-Fi 4</td>
      <td>802.11n</td>
      <td>2008</td>
      <td>72 to 600</td>
      <td>2.4/5</td>
    </tr>
    <tr>
      <td>Wi-Fi 3</td>
      <td>802.11g</td>
      <td>2003</td>
      <td>6 to 54</td>
      <td>2.4</td>
    </tr>
    <tr>
      <td>Wi-Fi 2</td>
      <td>802.11a</td>
      <td>1999</td>
      <td>6 to 54</td>
      <td>5</td>
    </tr>
    <tr>
      <td>Wi-Fi 1</td>
      <td>802.11b</td>
      <td>1999</td>
      <td>1 to 11</td>
      <td>2.4</td>
    </tr>
    <tr>
      <td>Wi-Fi 0</td>
      <td>802.11</td>
      <td>1997</td>
      <td>1 to 2</td>
      <td>2.4</td>
    </tr>
  </tbody>
</table>

And Bluetooth communication can be done over 2.4 Ghz and with 79 to 40 channels depending upon the needs.
So to make a system that can detect these type of apps we must have to understand working of these apps .

These apps allow users to connect to each other over Wi-Fi and Bluetooth without the need of internet or cellular connection creating a local area network but with these type of apps this network can be chained up to create a WAN so to detect this type of network we have to enter the network using wifite or Namp then by creating a fake ssid of same name we can perform a false handshake then after entering in that network we can check each nodes and no of connection to that particular node.


