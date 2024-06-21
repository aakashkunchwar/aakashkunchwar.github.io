# Capstone Computer Networks and Cisco Devices Lab

### Task 1: Introduction to the guided project and the Packet Tracer:

1. In this first task you will be introduced to Cisco Packet Tracer. Packet Tracer is a cross platform visual simulation tool designed by Cisco systems that allows users to create network topologies and imitate modern computer networks. The software allows users to simulate the configuration of Cisco routers and switches using simulated command line interface.

2. Packet Tracer also makes use of drag-and-drop user interface allowing users to add and remove simulated network devices as they see fit. To start using packet tracer, you need to log in with your Cisco Networking academy ID. 

3. If you do not have an idea already, click on the sign up button to create a new account, complete the registration process, log in with your account and come back when you're ready. Welcome back again and great job on completing this task. In this task you learned about the uses of Cisco Packet Tracer.

![A screenshot of a computer](<images/Picture 1.PNG>)


### Task 2: Identifying and connecting different network components using Packet Tracer:

1. Open Cisco Packet Tracer

2. Insert End Devices

Drag and drop devices from the "End Devices" menu onto the workspace. Examples of end devices include PCs, laptops, servers, and smartphones.
3. Connect End Devices to a Switch

Go to the "Connections" tab and click "Automatically Connect".
Click on the end device you want to connect, then click on the switch port you want to connect it to.
Repeat this process for all end devices.

4. Connect a Wireless Device (Optional)

Drag and drop a home router from the "Wireless Devices" menu onto the workspace.

The wireless device (smartphone) should automatically connect to the router.

Connect the home router to the switch using the "Automatically Connect" function.

5. Understand Network Media Network media are cables that connect network devices. Packet Tracer offers various media types, including copper straight-through cables and copper crossover cables.

6. Observe Network Topology

The way you connect your devices creates a network topology. This helps visualize your network structure.

7. Explore Logical vs. Physical Topology

Logical topology refers to how devices are connected logically, including addressing schemes. You can view this information by hovering over devices. Physical topology refers to the physical layout of the network cables and devices. You can switch to the physical view to see this.

![A screenshot of a computer](<images/Picture 2.PNG>)

![A screenshot of a computer](<images/Picture 3.PNG>)

![A screenshot of a computer](<images/Picture 4.PNG>)

![A screenshot of a computer](<images/Picture 5.PNG>)

![A screenshot of a computer](<images/Picture 6.PNG>)

![A screenshot of a computer](<images/Picture 7.PNG>)

![A screenshot of a computer](<images/Picture 8.PNG>)

### Task 3: Managing Cisco Devices:

**Connecting to a Cisco Device: A Step-by-Step Guide**

This guide outlines the methods for connecting to a Cisco device and navigating its operating system (Cisco IOS).

**Cisco IOS and Modes**

- Cisco devices run Cisco IOS, a network device operating system.
- To manage a device, you'll need to connect and enter commands.
- There are two access modes:
    - User EXEC (limited access for troubleshooting)
    - Privileged (full access for configuration)

**Connection Methods**

1. **Console Cable:**
    - For direct connection (laptop/PC) to the Cisco device (router, switch, firewall).
    - Used for initial setup or troubleshooting.
    - Requires a console cable.

2. **Telnet (Insecure - Lab Use Only):**
    - Remote connection over a network.
    - **Not recommended** due to security risks.
    - Requires a terminal emulation program (e.g., Putty).

3. **SSH (Secure):**
    - Secure remote connection over a network.
    - Recommended method for remote management.
    - Requires a terminal emulation program (e.g., Putty).

**Terminal Emulation Programs**

When connecting to real Cisco devices (not Packet Tracer), you'll need a separate program on your computer. Here are some options:

- Putty
- TerraTerm
- SecureCRT

**Entering Privileged Mode**

By default, you enter User EXEC mode upon connection. To access more features, enter privileged mode:

1. Type `enable` and press Enter.
2. You'll be prompted for a password. Enter the password and press Enter.
3. The device prompt will change to indicate privileged mode (e.g., `router#` instead of `router>`)

**Remember:**

- Use secure methods (SSH) for remote connections.
- Telnet is for labs only due to security vulnerabilities.

![A screenshot of a computer](<images/Picture 9.PNG>)

![A screenshot of a computer](<images/Picture 10.PNG>)


### Task 4: Securing access to cisco devices:

1. This guide outlines steps to secure Cisco device access in Cisco Packet Tracer, including console, Telnet, and privileged mode access.

2. Securing Console Access:

    Enter privileged mode: enable

    Enter global configuration mode: configure terminal

    Configure console line: line console 0

    Set password for console: password `<your_password>`

    Require login for console connection: login

    Exit configuration modes: exit

3. Securing Telnet Access:

   Enter privileged mode: enable

   Enter global configuration mode: configure terminal

   Configure virtual terminal lines: line vty 0 15

   Set password for Telnet: password `<your_password>`

   Require login for Telnet connection: login

   Exit configuration modes: exit

   Enable password encryption: service password-encryption

4. Securing Privileged Mode Access:

   Enter global configuration mode: configure terminal

   Set privileged mode password: enable secret `<your_password>` 

   Exit configuration modes: exit

5. Additional Tips:

   Use strong passwords for all access methods.

   Consider using SSH instead of Telnet for more secure remote access.

   Regularly review and update device configurations.

### Task 5: Capstone Activity:

Securing Cisco Device Access in Packet Tracer

This guide outlines the steps to secure console and telnet access on a Cisco router in Packet Tracer.

**Securing Console Port:**

1.  Connect to WAN Router 1 and enter `enable` mode.
2.  Use `configure terminal` to enter global configuration mode.
3.  Configure the console port (line 0) using `line console 0`.
4.  Set a password for the console with `password cisco`.
5.  Enforce login requirement with `login`.
6.  Exit configuration mode with `exit`.

**Testing Console Security:**

1.  Connect the Admin Laptop to WAN Router 1 using a console cable.
2.  Open a terminal emulator on the Admin Laptop.
3.  You should be prompted for a password. Enter "cisco" to log in.

**Securing Telnet Ports:**

1.  Return to WAN Router 1 and enter `enable` mode.
2.  Use `configure terminal` to enter global configuration mode.
3.  Configure virtual terminal lines (vty 0-15) with `line vty 0 15`.
4.  Set a password for all telnet ports with `password cisco`.
5.  Enforce login requirement with `login`.
6.  Exit configuration mode with `exit`.

**Testing Telnet Security:**

1.  On the Admin Laptop, open the Telnet/SSH application.
2.  Enter the WAN Router 1 IP address (192.168.1.1) and click "Connect".
3.  You should be prompted for a password. Enter "cisco" to log in.

**Checking Password Encryption:**

1.  On WAN Router 1, display the running configuration with `show running-config`.
2.  Verify if passwords are stored in plain text.
3.  Enable password encryption service with `service password-encryption`.

**Verifying Encryption:**

1.  Exit configuration mode and display the running configuration again.
2.  Passwords should now be encrypted.

![A screenshot of a computer](<images/Picture 11.PNG>)

Source: Introduction to Computer Networks and Cisco Devices, Coursera, Mohammed Al M.