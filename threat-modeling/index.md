# Introduction to Threat Modeling

A bit of an introduction...

Information security at Boeing is not in the security field. Rather, security at Boeing exists for the sole purpose of risk management.

Cybersecurity just happens to be the means by which managing risk is most effective.


## Why Threat Model

Threat models help us determine where risk may introduce itself into a system. The goal is not necessarily to *eliminate* the risk, but rather to 
understand where it is present in the system and in what capacity. 


## Basic diagrams

< A basic threat model >



# Basic Concepts


## Trust Boundary

@todo


## Attack Surface

@todo


## Risk

* What is risk?

* Strategies for risk management

Chapter 9?


## Some more advanced threat model diagrams

< A more advanced threat model



# STRIDE


## STRIDE

STRIDE is a mnemonic for the ways to introduce a threat into a previously secure system. 

STRIDE is a mnemonic to help identify, organize, and 



# **S**TRIDE


## Spoofing

Pretending to be something or someone that you're not.

* Violates the property of authentication

* Common targets are people, external entities, and trusted processes


## Spoofing Examples


## Spoofing Mitigation



# S**T**RIDE


## Tampering

Modifying something you're not supposed to modify.

* Violates the property of integrity

* Common targets are network traffic, memory, processes, and storage


## Tampering Examples


## Tampering Mitigation



# ST**R**IDE


## Repudiation

Claiming you didn't do something

* Violates the property of non-repudiation

* Common targets are processes - @todo


## Repudiation Examples


## Repudiation Mitigation



# STR**I**DE


## Information Disclosure

Exposing information to people who are not authorized to see it.

* Violates the property of confidentiality

* Common targets are storage, memory, and system information

* Infomration disclosure can lead to the exfiltration of classified, business-critical, or information that provides a competitive advantage. 


## Information Disclosure Examples


## Information Disclosure Mitigation



# STRI**D**E


## Denial of Service

Attacks designed to prevent a system from providing service, including by crashing it, making it unusably slow, or filling all its storage.

* Violates the property of availability

* Common targets are processes, storage, and data flows


## Denial of Service Examples


## Denial of Service Mitigation



# STRID**E**


## Elevation of Privilege

When a program or user is able to do things that they're not supposed to.

* Violates the property of authorization

* Common targets are application-level processes, system-level processes, and hardware exploits


## Elevation of Privilege Examples


## Elevation of Privilege Mitigation



# Game!


## Elevation of Privilege


