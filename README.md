# Threat Intelligence-Driven Cybersecurity Risk Management Tool

## Overview
The goal of this project is to bridge the gap between real-world attacker behavior (TTPs) and known software vulnerabilities (CVEs) using modern threat intelligence techniques and data-driven approaches.

## Problem Statement

Despite the availability of extensive vulnerability databases (like the NVD), security teams struggle to correlate:
- **TTPs**: How attackers operate (tactics and techniques)
- **CVEs**: Known vulnerabilities in software

This lack of direct mapping slows down risk analysis and limits the effectiveness of threat-informed defense strategies.

##  Objectives

- Map real-world attacker behavior (from sources like MITRE ATT&CK) to known CVEs
- Create a risk management tool that leverages this correlation
- Enhance security operations by providing actionable intelligence

##  Motivation

Examples of negligence that led to severe cyberattacks:

Target (2013) – Missed warning signs from a third-party vendor breach

Equifax (2017) – Failed to patch a known Apache Struts vulnerability

Marriott (2018) – Undetected breach that exposed millions of records

In 2023, cybercrime losses reached $12.5 billion, with groups like North Korea’s Lazarus Group causing nearly $300 million in damages.

## Features (Planned)

- CVE ↔ TTP correlation engine

- Dashboard for risk visualization

- Modular design for continuous threat feed updates

- Open-source threat data ingestion (STIX, TAXII)
