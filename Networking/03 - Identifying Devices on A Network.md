To **communicate** and **maintain order** devices must be both **identifiable** and **identifying** on a network. What use is it talking to someone if you don't know who they are?  \
: Humans have 2 main ways of being identified:-
- Name - *changeable*
- Fingerprint 

: Similarly devices also have 2 main ways of indentification:-
- Ip Address - *changes*
- A media access control *MAC* address

---

# IP Address
Simply a **I**nternet **P**rotocol Address is like a **unique number** given to a device for a period of time while conncted to a network, like a computer or phone.  \
It **identifies the device so that the data can be sent to the right place**  \
The IP address is **not permanant**, the same IP adress can be given to a different device at a different time

# Public vs Private IP Addresses

There are **2 types of IP addresses**:

##  Public IP Address
: A **public IP address** identifies your **network on the Internet**.

- Given by your **Internet Service Provider (ISP)**
- Websites and online services see this address
- All devices in your home usually share the same public IP address through your router

## 🏠 Private IP Address
: A **private IP address** identifies a **device inside your local network** (home, school or work).

- Given by your **router**
- Used for devices to communicate with each other
- Every device must have a **different private IP address**

## Example

| Device | Private IP | Public IP |
|---------|------------|-----------|
| Laptop | `192.168.1.77` | `86.157.52.21` |
| PC | `192.168.1.74` | `86.157.52.21` |

: See how:-
- The **private IP addresses are different** because each device needs its own address.
- The **public IP address is the same** because both devices are using the same Internet connection.

: It is basically like this:

- **Public IP Address** = Your home's street address.
- **Private IP Address** = The room number inside your house.

# IPv4 vs IPv6

Most devices use **IPv4** today.

An IPv4 address looks like this:

`192.168.1.77`

IPv4 uses **4 numbers** separated by dots.

The problem is that there are **billions of devices** connected to the Internet, so we are running out of IPv4 addresses.

To solve this issue, **IPv6** was created.

An IPv6 address looks like this:

`2a00:22c4:a531:c500:425f:cce6:c36b:f64d`

: ### Benefits of IPv6

-  It supports **far more IP addresses**
-  Helps solve the shortage of IPv4 addresses
-  It is more efficient than IPv4

---

# MAC Address

A **MAC (Media Access Control) address** is a **unique physical address** built into a device's network card.

Unlike a **IP address**, the **MAC address normally does not change**.

; A MAC address looks something like this:

`A4:C3:F0:85:AC:2D`

It is made up of **12 hexadecimal characters** (numbers and letters **0-9** and **A-F**) which are separated by colons.

: For example:

`A4:C3:F0 : 85:AC:2D`

- **First 6 characters** → Identify the company that made the network card.
- **Last 6 characters** → A unique number for that specific device.

: Think of it like this:
- **IP Address** = Your name (can change).
 - **MAC Address** = Your fingerprint (normally stays the same).

# MAC Address Spoofing

A device can **pretend to have another device's MAC address**.

This is called **MAC Spoofing**.

Some networks trust certain MAC addresses.

If an attacker copies a trusted MAC address, they may be treated as that trusted device.

For example:

- A firewall allows only the administrator's laptop.
- An attacker changes their MAC address to match the administrator's.
- The firewall thinks the attacker is the administrator.

This is why **MAC addresses should not be the only security method**.

# MAC Addresses on Public Wi-Fi

Some public Wi-Fi networks (such as cafés, hotels and airports) use MAC addresses to identify devices.

For example:

- ☕ One device can connect for free.
- 💷 You may have to pay to connect another device.
- The Wi-Fi remembers your device by its MAC address.
