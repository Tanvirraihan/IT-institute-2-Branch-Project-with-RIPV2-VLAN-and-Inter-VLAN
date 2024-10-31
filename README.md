# IT-institute-2-Branch-Project-with-RIPV2-VLAN-and-Inter-VLAN


Creative IT is a large training institute with two campuses located 20 miles apart. Campus 1 has three buildings:

Building 1: Houses the Admin, HR, Finance, and Business departments.
Building 2: Hosts the Faculty of Engineering & Computing and the Faculty of Art & Design.
Building 3: Contains a student lab and the IT department, which includes an FTP server.
The second campus, located in Mirpur, 20 miles from Campus 1, includes two sections: staff offices and a student lab.

Requirements:

A. Create a Network Topology:

Main Campus:

Building 1: Administrative departments including Management, HR, and Finance. The administrative staff PCs are distributed throughout the building and should share some networking equipment. (Hint: Use VLANs here.) The Faculty of Business is also located in this building.
Building 2: Faculty of Engineering & Computing and Faculty of Art & Design.
Building 3: Student labs and the IT department. The IT department hosts the university’s web server and other servers.
Note: There is also an email server hosted externally in the cloud.
Smaller Campus:

Faculty of Health and Sciences, with staff offices and student labs on separate floors.
B. Configuration Requirements:

1. Configure core devices and a few end devices to ensure end-to-end connectivity and access to both internal and external servers.
2. Each department/faculty should be on a separate IP network.
3. Configure switches with appropriate VLANs and Inter VLAN routing.
4. Use RIPv2 to provide routing for routers within the internal network.
5. Devices in Building A should acquire dynamic IP addresses from a router-based DHCP server.
