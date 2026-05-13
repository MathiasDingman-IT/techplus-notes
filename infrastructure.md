# Infrastructure

## Common Computer Devices

- **Computing devices** = All have a motherboard, processor, and storage, but vary in how users interact with input and output.

- **Desktop** = A Personal Computer (PC) that uses peripherals for input/output; e.g. screens, keyboards, mice, and speakers. Pros: Big and easy to fix/upgrade, large storage. Cons: Heavy, needs peripherals, and requires power from a socket.
- **Laptops/notebooks** = Everything a desktop has, but packed into a small case. Pros: Small and light, so easy to move; uses less electricity and has a battery. Cons: Difficult to fix, expensive, and not as powerful as desktops.
- **Tablets** = Mini computers with a touchscreen, no keyboard, and an operating system (OS). Hardware cannot be upgraded, and the OS cannot be changed.
- **Hybrid laptops** = 2-in-1 touchscreen tablets with a keyboard. Very expensive.
- **E-readers** = A type of device that uses e-ink so users can see the screen in sunlight. Very good battery life, which can last for days.
- **Servers** = Powerful computers that store lots of information and can perform multiple jobs for many users at one time. Have backup parts in case anything fails or breaks. Servers run continuously and are not meant to be turned off.
- **Gaming consoles** = Special computers used for gaming. Normally connected to TVs via HDMI cables. Have amazing graphics (graphics cards or GPUs) and use ray tracing.
- **Augmented Reality (AR)** = Puts computer-generated objects into the world around you.
- **Virtual Reality (VR)** = Takes users to a completely new world/environment.
- **Internet of Things (IoT)** = Devices that can be configured, report data, or be managed remotely over IP addresses. These include home appliances, thermostats, security systems, home assistants, deadbolt door locks, video doorbells, vehicles, streaming devices, medical devices, exercise equipment, and wearable devices.

## Common Internal Components

- **Motherboard** = Large circuit board that acts like the computer's spine. It links all components together by sending electrical signals to and from them. There are two types: ATX (12x9 inches) and microATX (9x9 inches). Motherboards work with specific CPUs and memory. AMD and Intel are the most common.
- *Proprietary* = Motherboard for a specific model or case; e.g. iPhone or laptop.
- *Standardized* = Motherboard that fits all cases; mostly desktops.Peripherals connect to the motherboard through buses via **Peripheral Component Interconnect (PCI)**. Today's systems use PCIe and come in x1, x2, x4, x8, and x16 (x1 and x16 are the most common).
- **Random Access Memory (RAM)** = Volatile storage that holds data and instructions when the computer is powered on and is lost when the system is turned off. Very fast and can be removed/replaced. RAM attaches using Dual Inline Memory Modules (DIMMs).
- **Central Processing Unit (CPU)** = The CPU is where input is processed and turned into output. Connects to the motherboard via Zero Insertion Force (ZIF). Intel and AMD are the most common manufacturers. Intel uses Land Grid Array (LGA). AMD uses Pin Grid Array (PGA), where thousands of pins are used. CPUs are categorised by how many bits they process. Modern computers use 64-bit processors, while older models use 32-bit processors. CPUs get very hot, so heat is removed using a heat sink, thermal paste, and fans.

- **Firmware/Basic Input/Output System (BIOS)** = Checks the hardware components on the motherboard during the Power-On Self-Test (POST). It is the first program to run when turning on a computer. BIOS is an old term, but the name has stuck. Today, computers use UEFI, which can be upgraded by "flashing" the ROM chip or downloading newer versions online (ASUSTeK and GIGABYTE are the most common).

- **Storage** = Includes both Read-Only Memory (ROM) (non-volatile) and RAM (volatile) and is how computers store information. Unlike RAM, ROM saves data permanently, is slower, cannot always be removed, and is programmable. Memory connects to the motherboard. DDR is the most common type, with DDR5 being the newest.

- **Graphics Processing Unit (GPU)** = A microprocessor used to display graphics for the user interface. Used for gaming and enhanced graphics. PCIe x16 is used for installation to the motherboard. NVIDIA is the biggest manufacturer. Resolution is shown in pixels; e.g. 1920 (horizontal) × 1080 (vertical). GPUs are also used for AI.

- **Network Interface Card (NIC)** = How the computer connects to the internet, either wired or wireless. Each NIC has its own unique MAC address in hexadecimal.

## Long-Term Storage

- **Serial Advanced Technology Attachment (SATA)** = The interface and method used to transfer data between the motherboard and storage devices.

- **Solid State Drives (SSD)** = Faster and longer-lasting than hard drives, but more expensive. Connect to the motherboard via M.2 or SATA (M.2 is faster).

- **Hard Disk Drives (HDD)** = The most common type of long-term storage. Data is stored using magnetic disks inside a protective case. They have moving parts, which can fail over time. Available in either 3.5 inches (desktops, 7200 RPM) or 2.5 inches (laptops, 5400 RPM).

- **Optical Drives** = A type of storage that uses light instead of magnetism; e.g. CD-ROM, DVD, and Blu-ray.

- **Flash Drives** = Portable storage devices that connect using USB ports (Type-A or Type-C).

- **Non-Volatile Memory Express (NVMe)** = The protocol, or set of rules, used to transfer data.

## Network Storage

- **Storage Area Network (SAN)** = A form of storage that uses storage devices and servers, which can be accessed through high-speed internet connections.

- **Network Attached Storage (NAS)** = A smaller version of a SAN where storage devices connect to the LAN via an Ethernet connection. They are configured with multiple hard drives in a Redundant Array of Independent Disks (RAID). This helps prevent data loss if one hard drive fails.

- **File Servers** = Powerful computers used for storing data 24/7.

- **Cloud Storage** = A way of storing data online by "renting" space in external data centres. They have **elasticity**, where storage can expand or contract based on the user's needs. They are also **scalable**, where more storage space can be provided if needed.

# Networking
- **Modem** = Takes the signal from the ISP and modulates/demodulates it into a form our devices can understand.
- **Router** = Takes the changed signal from the modem and sends it to our devices.
- **Latency** = Also known as ping rate. It is the time it takes for a signal to travel from our computer to an internet server.
- **Ethernet Cable / RJ-45 Connectors** = Consist of 8 wires grouped into 4 pairs. There are two standards: **T568A** and **T568B** (with T568B being the most common).

To install RJ-45 connectors, you need the following tools:
- **Crimper** = Connects the cable to the RJ-45 clip.
- **Punch Down Tool** = Pushes the 8 wires into a patch panel or wall jack.
- **Cable Tester** = Checks newly made cables.
- **Tone Probe** = Finds the start and end of a cable.

## Networking Types

- **Cable Internet** = Uses a coaxial cable, modem, and router. Speeds range from **10 Mbps – 2 Gbps** with latency between **10–50 ms**.
- **Digital Subscriber Line (DSL)** = Uses a telephone line, modem, and router. Speeds range from **5–50 Mbps** with latency between **20–50 ms**.
- **Fiber Internet** = Uses fiber optic cable and a router. Speeds range from **100 Mbps – 25 Gbps** with latency between **10–25 ms**.
- **Wireless Internet** = Uses a modem and router. Speeds range from **40–300 Mbps** with latency between **10–25 ms**. Examples include radio waves, satellite, and cellular connections.
- **Satellite Internet** = Uses a satellite dish, modem, and router. Speeds range from **3–250 Mbps** with latency of **100 ms or more**.
- **Fixed Wireless** = Uses an antenna, modem, and router. Speeds range from **1–30 Mbps** with latency between **20–60 ms**.

> **Note:** Wireless internet (Wi-Fi) is standardized under the **IEEE 802.11** family of standards.

# Virtualization

- **Virtualization** = A computing environment where multiple operating systems can be installed and run independently on a single physical device.

## Requirements1.
**Host Machine** = A physical computer that provides hardware resources such as CPU, memory, and storage.
**Hypervisor / Virtual Machine Manager** = Software that manages virtual machines.

- **Type 1 Hypervisor** = Installed directly on the host hardware and has direct access to system resources.
- **Type 2 Hypervisor** = Runs as an application on the host operating system and must request permission from the OS to access hardware.

**Guest Operating System** = The operating system installed inside the virtual environment.

# Cloud Services

- **Software as a Service (SaaS)** = Applications accessed through a web browser. The provider (such as Gmail or Google Workspace) manages the servers, hardware, operating system, and updates.
- **Platform as a Service (PaaS)** = Provides users with development tools, operating systems, and software platforms so they do not need to build them themselves. Commonly used by developers and database administrators. Examples include Oracle, MySQL, Java, Windows, and Linux environments.
- **Infrastructure as a Service (IaaS)** = Provides users with virtualized hardware resources such as servers, routers, and storage. It is often cheaper than purchasing physical equipment. Examples include AWS and Microsoft Azure.

## Cloud Deployment 

- **Public Cloud** = Users pay to access shared cloud infrastructure.
- **Private Cloud** = A dedicated cloud environment for a single organization or user.
- **Hybrid Cloud** = A combination of both public and private cloud environments.
