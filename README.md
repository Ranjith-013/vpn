# VPN Testing and Privacy Evaluation Report

##  Objective
To evaluate the effectiveness of a free VPN service in terms of:
- Changing the IP address
- Encrypting browsing traffic
- Measuring speed before/after VPN
- Assessing encryption and privacy features

---

## Steps Followed

### 1. **Chosen VPN Service**
```text
VPN: ProtonVPN (Free Plan)
Website: https://protonvpn.com
Reason: No data cap, strict no-logs policy, open-source
2. Installation and Setup

Platform: Windows 11
Protocol Used: WireGuard (UDP)
Connected Server: United States - US-FREE#30
Connection Status: Protected ✅

3. IP Address Check (Before VPN)

IP: 27.7.103.116
ISP: Hathway Cable and Datacom
Location: Mumbai, Maharashtra, India
📸 Verified via whatismyipaddress.com

4. IP Address Check (After VPN)

VPN IP: 143.244.44.172
VPN Location: New York City, USA
ISP: DataCamp Limited
📸 Confirmed IP changed successfully

5. HTTPS Traffic Encryption

Website tested: https://www.instagram.com
Browser Security Info: Connection is secure ✅
Certificate: Valid SSL/TLS certificate detected

6. Speed Test Comparison
🔻 Without VPN
Ping: 4 ms
Jitter: 2 ms
Download: 143.1 Mbps
Upload: 129.6 Mbps
ISP: Hathway
🔺 With VPN
Speed: Slightly reduced (due to server load ~87%)
Ping: Increased (expected)
🔒 VPN Encryption & Privacy Features

Provider: ProtonVPN
Encryption: AES-256 + RSA 4096-bit / Curve25519
Protocols Supported: OpenVPN, IKEv2, WireGuard
Logs Policy: No logs (verified)
Jurisdiction: Switzerland (strong privacy laws)
Source Code: Open-source clients (audited)
📄 Summary
✅ Benefits
🛡️ Hides IP and protects location

🔐 Encrypts browsing activity over public Wi-Fi

🌐 Access geo-blocked or restricted websites

🚫 Prevents ISP-level tracking

⚠️ Limitations
🐢 Slightly slower browsing speeds on free VPN

🌍 Limited server locations in free plan

🚧 May not bypass all streaming service blocks

🎯 Doesn’t prevent browser fingerprinting or phishing

📎 Conclusion
Using ProtonVPN's free plan successfully masked the IP address, ensured encrypted browsing, and maintained reasonable performance. It's a solid choice for basic privacy needs.

Tested on:
📅 Date: July 4, 2025
🖥️ Device: Windows 11
🌐 Browser: Microsoft Edge
