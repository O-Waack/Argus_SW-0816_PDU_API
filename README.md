# Argus SW-0816 PDU API

## Summary
A python API wrapper for [Argus PDU SW-0816](https://www.inter-tech.de/produktdetails-174/SW-0816_EN.html) and identical types such as e.g. Intellinet PDU to use the functions of the poor web interface via an instantiation in a commandline tool.

Since the firmware as well as the proprietary Windows software (which does not work for me) are the same for the identically constructed devices, I used the original wrapper of the Intellinet PDU (thanks for this go to CodingRobot) and adapted it to my needs, expanded it and made changes.

## Identical models
[Intellinet PDU 163682](https://intellinetnetwork.eu/products/intellinet-en-19-intelligent-8-port-pdu-163682)

## Python package dependencies:
 - [requests](https://pypi.org/project/requests) (pip install requests)
 - [lxml](https://pypi.org/project/lxml) (pip install lxml)
 - [urllib](https://pypi.org/project/urllib3) (pip install urllib3)

## Further links and data of the PDU

Product website of the distributor: https://www.inter-tech.de/produktdetails-174/SW-0816_EN.html

  

Example pictures from the distributor website:

  

![Argus PDU SW-0816 1](https://www.inter-tech.de/files/images/ipc/88887284/88887284/1_pdu_sw-0816_homepage.jpg)

  

**WARNING: As noted by the original author, the security functionality of the PDU is poor and should be used with caution in production environments (i.e. when an external connection may be possible).**