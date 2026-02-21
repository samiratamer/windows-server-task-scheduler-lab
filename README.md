# Windows Server Task Scheduler Lab

A system administration lab demonstrating the creation and management of automated scheduled tasks on Windows Server 2022 within an Active Directory domain environment, using VirtualBox virtual machines.

## What Was Configured
- Created a StartNotePad task triggered at domain user login on a remote server (ST-SUM25-S22-2)
- Configured task to run under a specific domain user account (SAVN\domainUser01)
- Verified task execution via Task Manager on the remote system
- Created a displayDateMessage task that runs a PowerShell script at logon for any user
- Registered and verified both tasks in the Task Scheduler Library

## Environment
- Windows Server 2022
- VirtualBox virtual machines
- Active Directory domain (SAVN)
- Windows Task Scheduler
- PowerShell scripting

## Skills Demonstrated
- Windows Server administration
- Active Directory user and domain management
- Automated task scheduling and configuration
- Remote system management
- PowerShell script execution via scheduled tasks
- Virtual machine administration

## Files
- `Project_6.pdf` — full lab documentation with screenshots showing each configuration step

## Course
System Administration & Maintenance (CNT 4603) – University of Central Florida
