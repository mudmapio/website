---
title: "Management of multiple firewalls"
subtitle: "Get a real picture of all your firewalls in one location"

# meta description

description: "Mudmap is built to handle multiple simultaneous connections"
draft: false
---

## Manage all your firewalls from one location

If you're an IT services provider, or just a one-person show but need to
maintain several devices, Mudmap has your covered.

I did this myself and I grew tired of it so I started Mudmap. It's now possible
to register many or all of your managed pfSense firewalls using this platform.

As a one-person shop, or even a huge organisation some common questions might
arise.

- How secure is this? 
- What does it look like?
- Are there limitations 
  
### Secure but internet facing 

To remotely access firewalls, either it will need to be
accessible over SSH or a VPN. Mudmap uses SSH as its transport layer, and will
only do so using public key authentication.

It does not lock you into using port 22 - you can pick whatever port suits you.

Lastly, Mudmap creates its own user on the firewall and does not allow access
to anything other than its API. Access to the API also requires authentication
between Mudmap's server and the device API. No two devices share API
credentials.

### Multiple devices displayed in one page 
Once a device is connected to our
servers, it will be able to read and update information on the firewall.

Mudmap provides a convenient interface to view all connected devices at a
glance, get the version and online status of each device. It is a near
real-time service, designed to provide great visuals without any impact to the
firewall's performance.

It is also possible to view a firewall in detail. Mudmap offers a familiar feel
and layout to the traditional pfSense user interface. All major functionality
found in a devices user interface also exists in the detailed view within
Mudmap's dashboard.

Put simply, Mudmap is the **ideal solution** for managing multiple firewalls across
many customers.

