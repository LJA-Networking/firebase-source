# Layer 1

## OSI model
**7 layers**  
For OSI, layer 7 is 1st while layer 1 is 7th
Layers 7, 6, and 5 are classified as software layers  
Layers 4, 3, 2, and 1 are classified as hardware layers

<table>
                <tr>
                    <th>Layer</th>
                    <th>Name</th>
                    <th>PDU</th>
                    <th>Functions</th>
                    <th>Notes</th>
                </tr>
                <tr>
                    <td>Layer 7</td>
                    <td>Application</td>
                    <td>Data</td>
                    <td>Direct user communication</td>
                    <td ><a href="#layer-7">Layer 7 Notes</a></td>
                </tr>
                <tr>
                    <td>Layer 6</td>
                    <td>Presentation</td>
                    <td>Data</td>
                    <td>Data formatting and translation</td>
                    <td ><a href="#layer-6">Layer 6 Notes</a></td>
                </tr>
                <tr>
                    <td>Layer 5</td>
                    <td>Session</td>
                    <td>Data</td>
                    <td>Controls connections between devices</td>
                    <td><a href="#layer-5">Layer 5 Notes</a></td>
                </tr>
                <tr>
                    <td>Layer 4</td>
                    <td>Transport</td>
                    <td>Segments</td>
                    <td>Transfering data from a source host to a destination host</td>
                    <td><a href="#layer-4">Layer 4 Notes</a></td>
                </tr>
                <tr>
                    <td>Layer 3</td>
                    <td>Network</td>
                    <td>Packets</td>
                    <td>Transfering packets from seperate networks</td>
                    <td><a href="#layer-3">Layer 3 Notes</a></td>
                </tr>
                <tr>
                    <td>Layer 2</td>
                    <td>Data Link</td>
                    <td>Frames</td>
                    <td>Routing within a local network</td>
                    <td><a href="#layer-2">Layer 2 Notes</a></td>
                </tr>
                <tr>
                    <td>Layer 1</td>
                    <td>Physical</td>
                    <td>Bits</td>
                    <td>Physical/Wireless connections between devices</td>
                    <td><a href="#layer-1">Layer 1 Notes</a></td>
                </tr>
            </table>
        <br>
        <hr>
        <div class="split-container">
        <div class="column">
        <p id="layer-7">Layer 7 Notes</p>
        <ul>
            <li>Services</li>
            <ul>
                <li>HTTP - Port 80</li>
                <li>HTTPS - Port 443</li>
                <li>DNS - Port 53</li>
                <li>SMTP - 25 (older)/587 (newer)</li>
            </ul>
                <li>Main functions</li>
            <ul>
                <li>File sharing</li>
                <li>Message handling</li>
                <li>Database access</li>
                <li>Web browsers</li>
                <li>Email programs</li>
            </ul>
        </ul>
        <hr width="60%">
        <p id="layer-6">Layer 6 Notes</p>
        <ul>
            <li>Purpose</li>
            <ul>
                <li>Data formatting</li>
                <li>Data translation</li>
            </ul>
            <p>Encapsulation of outgoing messages</p>
            <ul>
                <li>Process of adding markers to data such as metadata or syntax markers to then be sent to layer 5</li>
            </ul>
            <p>Deencapsulation of incoming messages</p>
            <ul>
                <li>Process of removing markers from data to then be sent to layer 7</li>
            </ul>
        </ul>
        <hr width="60%">
        <p id="layer-5">Layer 5 Notes</p>
        <ul>
            <li>Purpose</li>
            <ul>
                <li>Controls and manages the connection between devices</li>
            </ul>
            <li>Functions</li>
            <ul>
                <li>Manages user login</li>
                <ul>
                    <li>Also know as establishment</li>
                </ul>
                <li>Manages user logoff</li>
                <ul>
                    <li>Also know as termination</li>
                </ul>
                <li>Manages connections between local and remote applications</li>
            </ul>
        </ul>
        <hr width="60%">
        <p id="layer-4">Layer 4 Notes</p>
        <ul>
            <li>Purpose</li>
            <ul>
                <li>To convert data into segments</li>
                <ul>
                    <li>The process is called segmentation</li>
                </ul>
                <li>To attach a network and transport header</li>
                <li>To classify the transport protocol being used</li>
                <ul>
                    <li>TCP</li>
                    <ul>
                        <li>Transmission Control Protocol</li>
                        <li>Checks for complete data</li>
                        <li>Slower</li>
                        <li>Requires a digital handshake to transfer data</li>
                    </ul>
                    <li>UDP</li>
                    <ul>
                        <li>User Datagram Protocol</li>
                        <li>Does not check for complete data</li>
                        <li>Faster</li>
                        <li>Does not require a digital handshake</li>
                        <li>No guarantee of delivery, ordering or duplicates</li>
                    </ul>
                </ul>
            </ul>
        </ul>
        <hr width="60%">
        <p id="layer-3">Layer 3 Notes</p>
        <ul>
            <li>Purpose</li>
            <ul>
                <li>To route packets to other connected networks</li>
                <li>Responsible for packet forwarding</li>
                <li>Assigns and manages IP (Internet Protocol) address</li>
            </ul>
        </ul>
        <hr width="60%">
        <p id="layer-2">Layer 2 Notes</p>
        <ul>
            <li>Purpose</li>
            <ul>
                <li>Responsible for routing data within a LAN</li>
                <li>Routes data via a MAC address</li>
            </ul>
            <li>This is also where 802.3 Ethernet and 802.11 Wi-Fi standards operate</li>
        </ul>
        <hr width="60%">
        <p id="layer-1">Layer 1 Notes</p>
        <ul>
            <li>Purpose</li>
            <ul>
                <li>Responsible for the physical/wireless connections between devices</li>
            </ul>
            <li>Uses mediums such as copper, fiber or radio</li>
            <li>Connections voltage standards for devices</li>
        </ul>
<hr>
<h3><strong>Devices</strong></h3>
            <ul>
                <li>Hubs</li>
                <li>Repeaters</li>
                <li>Media Converters</li>
                <li>Network interface cards (NICs)</li>
                <li>Cables and Connectors</li>
                <li>Antennas and Transceivers</li>
            </ul> 
            <h3><strong>Ethernet/Coaxial</strong></h3>
            <p>Shielding</p>
            <ul>
                <li>Unsheilded Twisted Pair (UTP)</li>
                <ul>
                    <li>Most common type</li>
                    <li>Relies on the twisting of the wire to cancel out interference</li>
                    <li>Cheaper to make but more susceptible to interference</li>
                </ul>
                <li>Shielded Twisted Pair (STP)</li>
                <ul>
                    <li>Includes a metallic shield (often out of copper)</li>
                    <li>Made to cancel out/protect again EMI (Electromagnetic interference)</li>
                    <li>Uses a grounding wire to carry away intercepted interference</li>
                </ul>
            </ul>
            <p>RJ-45 Pin layout</p>
            <table>
                <tr>
                    <th>Pin #</th>
                    <th>T568A</th>
                    <th>T568B</th>
                </tr>
                <tr>
                    <td>1</td>
                    <td>White/Green</td>
                    <td>White/Orange</td>
                </tr>
                <tr>
                    <td>2</td>
                    <td>Green</td>
                    <td>Orange</td>
                </tr>
                <tr>
                    <td>3</td>
                    <td>White/Orange</td>
                    <td>White/Green</td>
                </tr>
                <tr>
                    <td>4</td>
                    <td>Blue</td>
                    <td>Blue</td>
                </tr>
                <tr>
                    <td>5</td>
                    <td>White/Blue</td>
                    <td>White/Blue</td>
                </tr>
                <tr>
                    <td>6</td>
                    <td>Orange</td>
                    <td>Green</td>
                </tr>
                <tr>
                    <td>7</td>
                    <td>White/Brown</td>
                    <td>White/Brown</td>
                </tr>
                <tr>
                    <td>8</td>
                    <td>Brown</td>
                    <td>Brown</td>
                </tr>
            </table>
            <hr>
            <p>Twisted-Pair Cable Ratings</p>
            <table>
                <tr>
                    <th>Class</th>
                    <th>Speed</th>
                    <th>Bandwidth</th>
                    <th>Distance</th>
                </tr>
                <tr>
                    <td>CAT 5</td>
                    <td>100 Mbps</td>
                    <td>100 Mhz</td>
                    <td>100 m</td>
                </tr>
                <tr>
                    <td>CAT 5e</td>
                    <td>1 Gbps</td>
                    <td>100 MHz</td>
                    <td>100 m</td>
                </tr>
                <tr>
                    <td>CAT 6</td>
                    <td>1 Gbps</td>
                    <td>250 MHz</td>
                    <td>100 m</td>
                </tr>
                <tr>
                    <td>CAT 6a</td>
                    <td>10 Gbps</td>
                    <td>500 MHz</td>
                    <td>100 m</td>
                </tr>
                <tr>
                    <td>CAT 7</td>
                    <td>10 Gbps</td>
                    <td>600 MHz</td>
                    <td>100 m</td>
                </tr>
                <tr>
                    <td>CAT 8</td>
                    <td>25/40 Gbps</td>
                    <td>2000 MHz</td>
                    <td>30 m</td>
                </tr>
            </table>
            <hr>
            <h3><strong>Coaxial Plugs and cables</strong></h3>
            <ul>
                <li>RG-6 Coaxial cable</li>
                <ul>
                    <li>Made up of a center copper core, insulation, foil shielding, and an outer jacket.</li>
                    <li>Used for CATV/Satellite connections</li>
                </ul>
                <li>RG-59 Coaxial cable</li>
                <ul>
                    <li>Made up of a center copper core, insulation, a bradided shield, and an outer jacket.</li>
                    <li>Used for CCTV/Analog Video</li>
                </ul>
            </ul>
            <ul>
                <li>F-Type Connector</li>
                <ul>
                    <li>Uses an externally threaded metal conductor</li>
                    <li>Commonly used for cable modems (DOCSIS), Satellite TV, and Cable TV (CATV)</li>
                </ul>
                <li>BNC Connector</li>
                <ul>
                    <li>Uses a metallic bayonet twist lock mechanism</li>
                    <li>Commonly used in enterprise WANs, Thinnet, CCTV and broadcasting</li>
                </ul>
            </ul>