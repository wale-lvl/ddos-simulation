# DDoS Attack Simulation

I Simulated a TCP SYN Flood DDoS attack on a local Apache web server using `hping3`, and analyzed traffic with `Wireshark`.

## Tools Used

* Kali Linux
* hping3
* Wireshark
* Apache2 Web Server

## What I Learned

* TCP SYN flooding techniques
* How to detect traffic anomalies in Wireshark
* Basics of network forensics

## Commands Used

```bash
sudo apt install apache2 hping3
sudo systemctl start apache2
sudo hping3 -S -p 80 -i u1000 127.0.0.1

```
