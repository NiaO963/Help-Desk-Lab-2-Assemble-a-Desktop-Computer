# Help-Desk-Lab-2- Dissamble and Assemble-a-Desktop-Computer

In a Help Desk or Desktop Support role, the ability to identify, install, and troubleshoot physical hardware is essential. This lab documents the end-to-end disassembly and assembly of a desktop computer, ensuring all subsystems (Power, Processing, Storage, and Cooling) are correctly integrated and functional.
______________________________________________________________________________________

Part 1: Disassembly


Phase 1: Peripheral & External Disconnection
I began by removing all external input/output devices and the side panel. This stage involves a visual inspection of the internal layout to identify any proprietary locking mechanisms or non-standard cable routing.

Phase 2: Expansion Cards & Storage
I removed the Dedicated GPU and any PCIe expansion cards (Wi-Fi/Sound cards). Following this, I disconnected the SATA and Power cables from the SSD/HDD and removed the drives from their respective bays.

Key Action: Releasing the PCIe slot safety latch before pulling the GPU to prevent slot damage.

Phase 3: Power Supply Unit (PSU) Extraction
I systematically unplugged the 24-pin Motherboard power, 8-pin CPU power, and peripheral cables. The PSU was then unscrewed and removed from the chassis.

Key Action: Managing the "cable octopus" to ensure no wires snagged on motherboard components during extraction.

Phase 4: Core Component Removal (CPU & RAM)
I unseated the RAM modules and removed the CPU cooling assembly. Finally, I carefully removed the CPU from the socket and placed it in an anti-static protective tray.

Key Action: Using isopropyl alcohol (90%+) to clean the old thermal paste off the CPU and Heatsink for clean storage.

4. Summary & Conclusion
The disassembly was completed successfully with zero "re-work" or physical damage to the hardware. All components were categorized and stored in anti-static packaging.

Key Takeaways:

Organization: Keeping track of different screw sizes (M3 vs. #6-32) is critical for preventing stripped threads during future maintenance.

Careful Extraction: Demonstrated the patience required to work around tight mATX/ITX cases without scratching the motherboard PCB.

Readiness: The chassis and components are now verified as "Clean" and ready for either individual testing or a full system upgrade.


______________________________________________________________________________________

Part 2: Assembly 

Phase 1: Motherboard "Breadboarding"
Before mounting the board into the chassis, I installed the CPU, RAM, and M.2 storage. This "breadboarding" phase allows for a quick POST test to ensure the core components are functional before final cable management.

Key Action: Seating the CPU and aligning the "Triangle" markers to prevent pin damage.

Phase 2: Chassis Integration & ESD Safety
I installed the I/O shield and mounted the motherboard using the correct standoff pattern. Proper grounding was maintained throughout to prevent Electrostatic Discharge (ESD) damage to sensitive CMOS circuits.

Key Action: Securing the motherboard and ensuring no contact between the board and the metal tray.

Phase 3: Power Distribution & Cooling
I connected the 24-pin ATX power and 8-pin CPU power cables. I then installed the CPU cooling solution, ensuring even pressure for optimal heat dissipation.

Key Action: Connecting the Front Panel Headers (Power SW, Reset SW, HDD LED) according to the motherboard manual.

Phase 4: Verification & POST
The final step involved connecting a monitor and peripherals to verify the Power-On Self-Test (POST). I accessed the UEFI/BIOS to confirm that the CPU temperature was stable and that all RAM modules and storage drives were recognized by the system.

4. Summary & Conclusion
The assembly was successful, and the system passed the initial POST on the first attempt.

Key Takeaways:

Precision: Verified that RAM was seated in the correct slots (A2/B2) for dual-channel optimization.

Documentation: Utilized the motherboard manual to accurately map the front panel connectors, a common "pain point" in hardware support.

Resolution: The system is now ready for OS deployment (Windows 11/Linux) and stress testing.
