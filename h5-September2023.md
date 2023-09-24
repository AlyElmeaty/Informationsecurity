# X)
## 2.3 One-Way Functions:  
One-Way Functions are mathematical functions that are relatively easy to compute in one direction but extremely difficult to reverse.
The key property of one-way functions is that given an input, it's computationally infeasible to find the original input value (pre-image) that maps to that output.
One-way functions are the foundation of many cryptographic techniques, including encryption, digital signatures, and password hashing.
Schneier emphasizes the importance of selecting one-way functions carefully since the security of cryptographic systems relies on their properties.  

## 2.4 One-Way Hash Functions:  
One-Way Hash Functions are a specific type of one-way function that takes an input (or message) and produces a fixed-length string of characters, known as a hash value or digest.
Key properties of one-way hash functions include:
Pre-image Resistance: Given a hash value, it's computationally infeasible to find the original input.
Collision Resistance: It's difficult to find two different inputs that produce the same hash value.
One-way hash functions are commonly used for data integrity verification, password storage, and digital signatures.
Schneier highlights that the security of cryptographic systems depends on the strength and properties of the chosen one-way hash functions.  

## Särökaari 2018

**Email Phishing Presentation Overview:**
- Niklas Särökaari's talk focused on email phishing.
- He introduced himself as a security professional and master's thesis researcher.

**Understanding Why People Click on Phishing Links:**
- A German study in 2016 revealed reasons people click phishing links: curiosity (34%), expectation (30%), and trust in sender (16%).

**Ethical Considerations:**
- Phishing should be done with permission and legally compliant.
- Privacy concerns and adherence to data protection laws are crucial.

**Email Validation Systems in Phishing:**
- Email validation methods like SPF (Sender Policy Framework) and DKIM (DomainKeys Identified Mail) enhance email legitimacy.
- Phishing campaigns often configure SPF and DKIM records for reputation.

**Bypassing Email Protection Mechanisms:**
- Attackers can bypass protection by configuring SPF/DKIM, buying domains, and making emails appear reputable.
- Methods include using specific file formats or attachments that evade detection.

**Methods of Phishing Through Email:**
- Techniques include using Dynamic Data Exchange (DDE) for code execution, obfuscation, and avoiding macros.
- Methods for evading filtering and web blocking, like whitelisting domains and graylisting, were explained.
- Website cloning is used to harvest credentials.

**Specific Phishing Techniques:**
- Use fully qualified domain names, HTTPS for encrypted traffic, and homograph attacks.
- Phishing emails mimic reputable sources (e.g., Gmail, IT departments) with urgent messages or package delivery notifications.

**Effectiveness of Phishing:**
- Phishing success increases with the number of emails sent.
- Even a small percentage of recipients clicking links can lead to successful attacks.
- Examples of phishing techniques, like urgent messages or using similar domains, were shared.

**Mitigation Measures:**
- Implement SPF and DKIM to block email spoofing.
- Owning similar-looking domains can protect against phishing.
- Educate users to detect and report phishing.
- Secure infrastructure through updates and use tools like phishing catchers.

**Reporting Phishing:**
- Few people report phishing attacks, estimated at 10-15%.
- Improved reporting methods for companies were encouraged.

**Language Quality and Phishing Effectiveness:**
- Poorly translated emails may be less successful in phishing.
- Phishing emails should pique curiosity or fear.

**Conclusion:**
- Phishing is easier in certain languages (e.g., Finnish).
- Users should remain skeptical and cautious.
- Proactive security measures are essential to combat phishing effectively.



# a) Installing hashcat
Step 1   
<img width="528" alt="image" src="https://github.com/AlyElmeaty/Informationsecurity/assets/142783003/a1538145-51a2-430b-bfcd-dd16e5e1b838">  
making dierectory  
<img width="519" alt="image" src="https://github.com/AlyElmeaty/Informationsecurity/assets/142783003/86eb03b2-b6f1-426e-9941-97f040587906">  
rockyou.txt  
<img width="532" alt="image" src="https://github.com/AlyElmeaty/Informationsecurity/assets/142783003/89a8a152-7ec4-4b7f-92bb-3456c77fd014">  

# b) Crack this hash: 8eb8e307a6d649bc7fb51443a06a216f
Using rockyou.txt  
<img width="510" alt="image" src="https://github.com/AlyElmeaty/Informationsecurity/assets/142783003/a79342f6-5d59-4cfb-9ab3-bf48a2b4d51d">  
The hash = 'february'  

# c) Gone phishing:  
I would create an email saying:  
"Hello,
Unfortunately you were hacked, I got access to your camera and browsing history, I could detect when you browse adult content and by my access to your camera, I recorded a video of you doing a very humiliating act during your browsing, I sent you a part of this video in this email, open it to make sure it is you.
You have 24 hours to contact me to try to convince not to post this video on social media and tag all your family and friends. You might convince me by some money, or let's see, maybe something else"

I will insert a malware instead of the "video" and when they try to press on the video to check if it is them, the malware will be installed and boom they get hacked.


