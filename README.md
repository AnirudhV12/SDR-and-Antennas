# SDR-and-Antennas
Exploring the build and use of different types of antennas to analyse their signals on an RTL-SDR V4 (Software-Defined Radio). 

## Introduction
As an Electronics and Communications Engineering student, I wanted to gain hands-on experience with various communication techniques. This led me to explore Software Defined Radios (SDRs) and their practical applications, including antenna design.

A radio is any kind of a device that wirelessly transmits or receives signals in the radio frequency
(RF) part of the electromagnetic spectrum (3KHz to 3000 GHz) to facilitate the transfer of information.

Traditional hardware based radio devices limit cross-functionality and can only be modified
through physical intervention. This results in higher production costs and minimal flexibility in
supporting multiple waveform modulation/demodulation standards.

A software-defined radio (SDR) is a radio in which some or all of the physical layer functions are software defined. It can be used to analyse signals of different analog modulation techniques, such as AM, FM, PM and even digital modulated waves such as ASK, FSK, PSK, QPSK, BFSK, etc.,

This repository is meant to primarily explore the various aspects of Antenna design and SDR implementation to analyse RF signals.

## Objectives

<i> To design, build and modify antennas to receive and analyse on an SDR: </i>

1. FM broadcast signals [88 MHz - 108 MHz]
2. ADS-B (Automatic Dependant Surveillance-Broadcast) signals of aviation [1090 MHz]
3. NOAA weather satellite images in real time
4. AIS (Automatic Identification System) of maritime traffic [162 MHz]

## Ancillaries to the Objectives

1. Building various types of antennas (Dipole, Yagi-Uda, Turnstile, etc.,) to suit the above stated objectives.
2. Improvisation of built antennas through modifications such as adding chokes, LNAs, etc., as per requirement.
3. Exploring the use of SDR#, a software application used to interface the RTL-SDR with a computer.
4. Adopting the use of coaxial cables and connectors.

