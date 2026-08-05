# IT351_Project-Phase-1
 IT351 Project Phase 1
 ## Team Contributions (Phase 1)

### Student 1: Abdulrahman Sulaiman Albalawi (Installation & Topology Building)

**1. Cisco Packet Tracer Installation:**
I downloaded and installed Cisco Packet Tracer version 9.0.0 on my computer to begin our network design. 

**2. Network Topology Construction:**
I created the initial network topology layout according to the project specifications. I selected and placed the main network nodes, including the routers and switches, and connected them using the initial wiring to form the baseline infrastructure for both campuses.

### Student 2: Oday Othman Alharbi (IP Addressing & Future Plan)

**1. IP Addressing Strategy:**
I designed a private IP addressing plan to organize our network efficiently. Each location has its own subnet and default gateway to ensure security and logical separation:
* **Computer Lab (LAN 1):** `172.16.10.0/24` — Gateway: `172.16.10.1`
* **Admin Office (LAN 2):** `172.16.20.0/24` — Gateway: `172.16.20.1`
* **Library (LAN 3):** `172.16.30.0/24` — Gateway: `172.16.30.1`
* **Faculty Office (LAN 4):** `172.16.40.0/24` — Gateway: `172.16.40.1`
* **WAN Connection:** `10.10.10.0/30` — To connect the Main Campus and Branch Campus routers.

**2. Next Steps & Future Milestones:**
In the next phase of the project (Phase 2), our team will implement the following tasks:
* Assign the planned IP addresses to all 12 computers.
* Configure the FastEthernet and Serial interfaces on both routers.
* Use the `ping` command to test connectivity and ensure successful communication across the network.

---

## Challenges and Verification
** Mohammed Turki Alotaibi ** 

During the implementation phase, one of the team members encountered a problem while building the network within Cisco Packet Tracer. They were having difficulty connecting devices, or the connections were unclear. We reviewed the network plans, verified the cable layout and connections, and made adjustments to resolve the issue, restoring functionality.

During the verification phase, I confirmed that the GitHub platform was functioning correctly and that team members were using their personal accounts. I verified that Google Docs was accessible for the project documentation.

I also checked the Cisco Packet Tracer project from the GitHub repository. The project works as required, and the network design functions without problems.

### Student 4: [Mubarak turkey almurjan] (Software Features & Documentation)

**1. Key Features of Cisco Packet Tracer:**
Cisco Packet Tracer is a powerful network simulation tool that helps us design, configure, and troubleshoot networks. The main advantages for our project are:
* **Simulation Mode:** It allows us to view data packet transmission step-by-step to test connectivity.
* **Device Variety:** It provides realistic routers, switches, and cables to mirror real-world networking environments.

**2. Final Network Topology Interface:**
I renamed all network devices to their final English labels inside the topology and ensured the design looks clear and organized.

---

##  Group Contributions Table

| Student Name | Assigned Role & Tasks in Phase 1 | Status |
| :--- | :--- | :--- |
| **Abdulrahman Sulaiman Albalawi** | Software installation, installation screenshots, and initial topology design. | **Completed** |
| **Oday Othman Alharbi** | Designed IP subnets, documented addressing decisions, and created the future plan. | **Completed** |
| **Mohammed Turki Alotaibi** | Documented team challenges, provided solutions, and verified all project links. | **Completed** |
| **[Mubarak turkey almurja]** | Renamed topology devices, captured final interface screenshots, and documented software features. | **Completed** |


---
# Phase 2: Network Implementation & Verification

## Completed Tasks
1. **Interfaces & IP Allocation:** Configured GigabitEthernet interfaces on routers and assigned static IP addresses to all 12 PCs across 4 LANs.
2. **WAN Connection:** Activated `Serial10/3/0` interfaces between MainCampus and BranchCampus with clock rate configuration.
3. **Static Routing:** Successfully added static routes (`ip route`) on both routers for cross-campus connectivity.
4. **Verification:** Executed `ping` commands from LAN 1 to distant LANs, achieving 100% reachability (0% packet loss).

---
# Group Members (CRN: 50574)

* **Student 1 (Leader):** Abdulrahman Sulaiman Albalawi (ID: S240051883)
* **Student 2:** Oday Othman Alharbi (ID: s240031018)
* **Student 3:** Mohammed Turki Alotaibi (ID: S230042360)
* **Student 4:** Mubarak Turkey Almurjan (ID: S230040176)
