# Operating Systems

## Introduction

Hi everyone and welcome to session five. In this session, we're going to be discussing an overview of operating systems. The learning objectives are to define operating systems, outline the core functions of the operating system, and lastly, to discuss the core components of an operating system.

## What is an Operating System?

An operating system is software that manages hardware resources, such as your RAM, your processor, your monitor, and your hard disk. An operating system exists virtually in all computers. We have operating systems on our mobile phones, on servers, on desktops, and on laptops - virtually all computers have this software.

The software manages hardware resources, manages your processor, manages your RAM, manages your keyboard, manages your memory, and manages your hard disk. Popular operating systems in the market include Windows, Apple, and Linux. They also have versions for mobile devices, such as Android.

## Core Functions of Operating Systems

### Process Management

Every running application is a process. When you work with a document on your laptop, you are working with a process. When you are watching a movie, that's a process. When you are editing a task, that's a process. When you are streaming or downloading a particular file from the internet, that's a process.

An application process can be in different states: start state, ready state, running, waiting, or exit. Your operating system manages these processes. For example, an operating system distributes CPU time across processes.

Imagine you have four or five applications running on your computer. These applications will compete for resources. You have word processing software competing for resources, video streaming applications competing for resources, and audio files competing for CPU resources and processor resources.

Without an operating system, most of these applications would just clog the processor because they would compete for resources and latch onto the processor, causing it to become clogged. The operating system distributes CPU time across processes. The CPU can decide to pause a processor when another application requires CPU resources. The OS can split processing time in split seconds, pausing one application (like word processing) and giving priority to another application that requires more computer resources (like video editing software).

The OS manages the processor by instructing it which processes to run and which to pause. Instructions are handed to the processor by the operating system.

### Hardware Management and Driver Loading

The OS instructs the processor to load third-party drivers, such as printer drivers, so that the operating system can communicate with external devices. When you plug printers or other output devices into computers and want to print, sometimes you receive instructions saying that the driver for that printer has not been loaded yet, meaning your printing system cannot communicate with that printer.

Your operating system cannot instruct your processor to send a particular job to that printer without the proper driver. Once you install the driver for the third-party hardware (in this case, the printer), then the operating system can understand the language of the printer. The print system can now instruct the processor to send jobs to the printer.

### Memory Management

Memory management is another function of the operating system. The OS manages RAM and instructs the processor to load applications onto memory. When you click on a particular application, your operating system instructs the processor to load the application onto the RAM so that execution can start.

Whatever application you open on your computer remains temporarily on the RAM. Once you close that application, it ceases to exist on your RAM. RAM means Random Access Memory. When you are done with a file, you need to close it.

For example, when you're done with a PowerPoint document after editing, adding images, sound, graphics, and other elements, you need to save your work and close the application. The operating system then instructs the processor to delete the file from memory.

The operating system acts like a chef in the kitchen, managing all these processes efficiently.

### File Management

The operating system supports different types of file systems and various file types - work files, video files, audio files, document files, and many others. When you click on a particular file (like an MP4 file), the system opens it. You can click on different file types - document files, text files - and the system supports different file formats.

File systems are usually organized in a hierarchy of directories. You might have a file, and within that file, you might have another file or folder. Within that folder, you can have another sub-folder, and within that sub-folder, you can have yet another sub-folder containing the actual file.

This hierarchical arrangement is managed by the operating system. When you click on a particular folder, you can navigate to another folder, then to another embedded folder to access your file. The operating system manages this navigation process and the relationships between different file types - videos, audio, documents, and various other file formats.

### Networking

The operating system also manages communication with other computers using transmission control protocols. You can connect your computer to another computer across the globe. This connection is managed by the operating system.

For example, the OS has utility software to help communicate with other machines using networking protocols. You can launch utilities and use protocols like ping to test connections. You can ping a particular server or computer to check if you can communicate with that device.

When you ping a computer and receive a response, it means that computer is alive and you can communicate with it. If there's no response, it means the computer is not accessible on the network. Your operating system manages this communication using the TCP protocol.

You can open the command prompt (CMD) in Windows and use ping commands to test network connectivity. For example, pinging www.google.com will show responses from Google's servers, confirming that the server is alive and you can communicate with it.

### Security

The operating system also secures files and folders. When a Word document has a password, the OS manages access control. If the wrong password is entered, access is denied. If the correct password is entered, access is granted.

You can password-protect particular Word documents and send them to colleagues over the internet. Once your colleague enters the correct password, that folder will open and the file will be accessible. If a wrong password is entered, that document will never open. This security feature is managed by the operating system.

## Core Components of Operating Systems

Now let's look at the core components of an operating system:

### Boot Loader

The first component is the boot loader. This section of the operating system downloads the operating system onto the RAM.

When you power on your machine, instructions are fetched from the BIOS. The BIOS sits on the motherboard and performs a Power-On Self-Test (POST), testing all hardware devices to ensure they are functioning properly.

Once the BIOS completes the POST, it loads the boot loader, which then loads the operating system into memory so the computer can start operating normally.

Once the BIOS verifies that all hardware components (hard disk, RAM, power unit, CPU) are functioning properly, the next stage is to extract the boot loader to load the operating system from the hard disk onto the RAM.

The operating system must be loaded from the hard disk to the RAM, and during this process, you may see loading messages or background information indicating that the system is being loaded. This is the section of the OS that loads the operating system onto the RAM and manages the boot process.

The boot process brings your operating system to life. Once the operating system is loaded to the RAM, you see the login screen where you can enter your password, log in, see your desktop, and access all system features. At that point, your operating system is fully in charge.

### Kernel

The kernel is the core component of the operating system. It manages the CPU and processor by giving out instructions, telling it what processes to handle, which processes to stop, which processes to start, and which processes to prioritize. The kernel also manages memory - when you launch an application, it resides on the RAM, and when you close that application, it leaves the RAM.

The kernel is the core of the operating system. It manages CPU, memory, and other hardware resources.

### Services and Daemons

The next component is services (also called daemons in Linux). These are software programs that run in the background without requiring any user interaction. These background applications could include Windows updates, security features, and other system processes that run automatically.

If these services require you to perform a restart of your machine, that will be communicated to you. These services operate in the background continuously.

### Shell

Operating system components also include a shell that provides a user interface for interaction with the operating system services. You can have a graphical user interface (GUI) that provides visual navigation through your desktop, folders, applications, and files.

You can also communicate with your operating system using a command line interface (CLI). In Linux systems, you can use the command line interface for navigation, creating folders, and performing various system operations. While you can also do these tasks in Windows, most users prefer the graphical user interface.

## Operating System Analogy: The Kitchen

To help understand how an operating system works, think of it like a chef in a kitchen:

- **The Chef (Operating System)**: Gives instructions to the kitchen assistant
- **The Kitchen Assistant (CPU)**: Executes the instructions given by the chef
- **The Slab/Chopping Board (RAM)**: Where you temporarily place items for processing
- **The Fridge/Freezer (Hard Disk)**: Where information is stored permanently

Here's how it works: The chef instructs the kitchen assistant to fetch cabbage from the fridge and put it on the chopping board. The kitchen assistant follows these instructions, retrieves the cabbage, and begins cutting it into sections as directed by the chef.

Similarly, the chef can instruct the assistant to fetch apples from the fridge, put them on the chopping board for processing, and then store the prepared food in appropriate locations.

Just as the chef tells the kitchen assistant what to do (dicing carrots, cutting vegetables, rinsing apples, or chopping potatoes), the operating system (chef) instructs the CPU (kitchen assistant) on what tasks to perform. The RAM (slab) is where information is stored temporarily, while the hard disk (fridge/freezer) is where information is stored permanently.

This analogy helps us understand the relationship between the BIOS and the operating system components working together in harmony.

## Summary

In this session, we covered:

1. **Definition of Operating Systems**: Software that manages hardware resources and enables user interaction with computer systems
2. **Core Functions**: Process management, hardware management, memory management, file management, networking, and security
3. **Core Components**: Boot loader, kernel, services/daemons, and shell

We've been able to connect these concepts and relate them to the overall sequence of how operating systems function. For further reading, you can explore additional resources on these topics.

Thank you very much, and I'll see you in the next class.
