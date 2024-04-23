---
sidebar_position: 1
---

# FreePBX Introduction

FreePBX is a web-based open-source graphical user interface (GUI) that manages Asterisk, a voice over IP and telephony server. FreePBX is licensed under the GNU General Public License version 3. FreePBX is a component of the FreePBX Distro, which is an independently maintained Linux system derived from the source code of the CentOS distribution, having Asterisk pre-installed. FreePBX was developed by Rob Thomas in 2004 and has since become the most widely deployed Asterisk GUI.

## Purpose of UseCallManager Patch

The UseCallManager patch provides enhanced interoperability between FreePBX and Cisco Collaboration endpoints running enterprise firmware.
Standard Cisco devices running enterprise firmware are designed to work with Cisco Unified Communications Manager (CUCM) and are not fully compatible with Asterisk. The UseCallManager patch allows Asterisk to work with Cisco Collaboration endpoints by emulating the behavior of CUCM.

## Purpose of FreePBX Integration

The standard UseCallManager patch developed by the authors at [https://usecallmanager.nz](https://usecallmanager.nz) is designed to work with Asterisk and does not provide any integration with FreePBX. The FreePBX Integration patch is designed to work with the UseCallManager patch and provides the following enhancements:

- **Web Interface**: The FreePBX Integration patch provides a web interface that allows users to configure the UseCallManager patch settings directly from the FreePBX GUI.

- **Configuration Management**: The FreePBX Integration patch allows users to manage the UseCallManager patch settings directly from the FreePBX GUI. Users can configure the UseCallManager patch settings, such as call options, voicemail management, and other settings, directly from the FreePBX GUI.
