# Software-defined networking (SDN)

Netwroks are difficult to manage because:
- Diversity of equipment on the network
- Proprietary technologies for the equipment

Simplify by dividing into planes:
- Control
- Data

History of SDN:
- Active networks
  - MOdes:
    - Capsule - carry code in data packets
    - Programmable router/switch
  - Contributions:
    - Programmable functions in the network to lower the barrier to innovation
    - Network virtualization, and the ability to demultiplex to software programs based on packet headers
    - The vision of a unified architecture for middlebox orchestration
- Control and data plane separation
  - Logically centralized control using an open interface to the data plane.
  - Distributed state management.
- OPnFlow API and networking OSes
  - Generalizing network devices and functions.
  - The vision of a network operating system.
  - Distributed state management techniques.


1. Data centers.
2. Routing.  With SDN, it is easier to update the router's state, and SDN can provide more control over path selection. 
3. Enterprise networks. SDN can improve the security applications for enterprise networks. 
4. Research networks.

1. Forwarding (match input and output links) - data plane 
2. Routing (find path from sender to receiver across the network) - control plane

1. Flow-based forwarding -  many headers can affect the resulting route, not just the dest IP
2. Separation of data plane and control plane
3. Network control functions
4. A programmable network

An SDN controller can be broadly split into three layers: 
1. Communication layer: communicating between the controller and the network elements
2. Network-wide state-management layer: stores information of network-state
3. Interface to the network-control application layer:  communicating between controller and applications