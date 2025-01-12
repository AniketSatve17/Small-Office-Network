# Small-Office-Network
![{63B6E80B-9BAB-4AB7-AC57-78506B8AA79E}](https://github.com/user-attachments/assets/47ef9a7a-d922-4e3a-9c2a-207d3fd87f2e)

## Introduction

This project designs a basic, secure, and scalable network for XYZ Company's new branch in Bonalbo, Australia. Utilizing a single Cisco router and switch, the network is segmented into three VLANs (Admin/IT, Finance/HR, and Customer Service/Reception) for enhanced security and network management. Each VLAN is equipped with wireless access for employee convenience. The network employs DHCP for automatic IP address assignment, ensuring seamless device connectivity and simplifying network administration.

## The Problem Statement

XYZ company is a fast-growing company in Eastern Australia with more than 2 million customers globally. The company deals with selling and buying of food items, which are basically operated from the headquarters. The company is intending to open a branch near the local village Bonalbo. Thus, the company requires young IT graduates to design the network for the branch. The network is intended to operate separately from the HQ network.

Being a small network, the company has the following requirements during implementation;

a) One router and one switch to be used (all CISCO products).

b) 3 departments (Admin/IT, Finance/HR and Customer Service/Reception)

c) Each department is required to be in different VLANS.

d) Each department is required to have wireless network for the users.

e) Host devices in the network are required to obtain IPv4 address automatically.

f) Devices in all the departments are required to communicate with each other.

Assume the ISP gave out a base network of 192.168.1.0, you as the young network engineer who has been hired, design and implement a network considering the above requirements.

## How to solve:

1) Download Cisco Packet Tracer: https://learningnetwork.cisco.com/s/packet-tracer-alternative-lab-solutions
2) Launch and get familiar with the packet tracer environment and its tools.
3) Read the above problem statement and understand it to get started.
4) Drag and drop the components/devices needed as per problem statement: (Router2911, Switch2960-24TT, Pc, Printer, AccessPoint-pt)
5) Connect the devices with cable.
6) Give the background color of your choice to differentiate between the departments, I have given Green: Admin/IT, Purple: Finance/HR, Yellow:  Customer Service/Reception.
7) Next is Subnetting, you can refer the subnetting provided in the image 

![{92ABB6D8-4838-46C7-8802-A24FC47D7932}](https://github.com/user-attachments/assets/89c9cb87-e858-4570-ba38-d725cc1b66e0)

8) Configuration of Vlan in switch.
9) Configure the Access Points with Username/Password.
10) Configure the Router.
11) Configure Sub-Interface.
12) Configure Devices with DHCP service.
13) Add wireless devices of your choice, I have added: (Laptops and Smartphones).
14) For device communication see the video.

## Device Communication Simulation:


https://github.com/user-attachments/assets/84a0adcd-fa8c-4889-9c5e-8569d6507485



