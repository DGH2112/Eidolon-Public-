# Eidolon-Public-

Author:   David Hoyle

Version:  1.7e

Date:     22 Feb 2020

Web Site: [Eidolon](https://github.com/DGH2112/Eidolon-Public-)

## Overview

This is an Excel add-in designed to allow you to import and export data from various format and create Time Location / Time Chaiage diagrams from any planning software.

## Usage

For details on how to use the software please refer to the HTML Help file (`Eidolon.chm`). It contains details on all the operations you can perform in Eidolon including a number of tutorials. There is also a brief video on how to use Eidolon on the above web page.

## Manual Installation

In order to install Eidolon's DLL manually you will need to be able to open `CMD.exe` (Command Prompt) as an **Administrator** of the machine on which you want to install Eidolon. You will not be able to register the software without these priviges.

You can change drive at the command prompt by typing the drive letter, a colon and then presing the enter button:

    D:

You can change directory by typing CD and the directory name and then pressing enter (directories with spaces in need to be enclosed in double quotes):

    CD "Program Files (x86)"

You can get a list of files and directories by type DIR and pressing enter.

    DIR

You can change to a parent directory by typing CD.. and pressing enter:

    CD ..

Once you have successfully navigated to the **Eidolon** directory containing the files you can register the DLL with the system by typing the below command and pressing enter:

    REGSVR32 EIDOLON.DLL

Conversely you can unregister the DLL with the system by typing the below command and pressing enter:

    REGSVR32 /U EIDOLON.DLL
