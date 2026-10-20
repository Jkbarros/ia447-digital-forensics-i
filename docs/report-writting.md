# Report writting

**Source:** [`Report writting.pdf`](../archive/canvas-submissions/Report%20writting.pdf)  
**Course:** IA 447 - Digital Forensics I (EMU)  
**Author:** Julio Barros

## Page 1

1. What is the Daubert standard? 
The Daubert standard has been influential in shaping the admissibility of expert 
testimony in U.S. courts, and it has been adopted in many states as well. It has led 
to more rigorous scrutiny of expert witnesses and their methodologies to ensure that 
only scientifically valid and reliable evidence is presented to juries. 
2. What is a forensic acquisition? What is a bit stream copy? 
Forensic acquisition is the process of creating a copy of digital evidence, and a bit 
stream copy is a specific type of forensic acquisition that duplicates all data on a 
storage device bit by bit, maintaining the integrity and completeness of the original 
evidence. 
3. What is the difference between public sector and private sector investigation? 
Public sector investigations are carried out by government agencies with legal 
authority and a primary focus on upholding laws and regulations in the public 
interest. Private sector investigations, on the other hand, are conducted by private 
entities or individuals to protect their own interests and often involve business-
related matters. 
4. What is a search warrant? What is the search warrant in a private sector 
investigation? How does a corporate office (private sector) usually manage 4th 
Amendment issues? 
It's important to note that the specific rules and regulations governing private sector 
investigations can vary by jurisdiction and may be influenced by industry-specific 
laws and regulations. Therefore, companies should consult with legal experts to 
ensure their investigative practices follow local and national laws. 
 
5. List a few examples of private sector crimes that could be investigated 
forensically. 
Employee Theft: Investigating instances of theft or embezzlement by employees, 
which may involve forensic accounting to trace financial transactions and digital 
forensics to examine electronic records. 
Intellectual Property Theft: Investigating the theft or unauthorized distribution of 
intellectual property, such as trade secrets, patents, or copyrighted material, which 
may require digital forensics to trace the origin and dissemination of stolen data. 
Data Breaches: Investigating data breaches to determine the source of the breach, 
the extent of data exposure, and the identification of responsible parties.

## Page 2

6. What is the difference between interviewing and interrogating a suspect? What 
role does a forensic report play in each? 
Interviewing: 
Purpose: Information-gathering, establishing facts, and identifying leads. 
Tone: Cooperative and less confrontational, aimed at building rapport. 
Role of Forensic Report: Minimal role, primarily used if specific evidence needs to 
be discussed. 
Interrogating: 
Purpose: Obtaining confessions or additional information from a suspect. 
Tone: More structured and assertive, may involve persuasion and confrontation. 
Role of Forensic Report: Crucial role, often used to confront suspects with evidence 
and encourage statements or confessions. 
In both cases, forensic reports can corroborate or challenge information and guide 
questioning, but all actions must be within legal boundaries and respect the rights of 
individuals involved. 
 
7. What is a chain of custody? What is forensic acquisition? What is a bit-stream 
image? How do investigators secure and preserve evidence? 
Chain of Custody: 
A documented record of evidence possession and handling. 
Ensures the integrity and admissibility of evidence in legal proceedings. 
Tracks who had custody, when, where, and any changes in condition. 
 
Forensic Acquisition: 
In digital forensics, the systematic collection and preservation of digital evidence. 
Involves creating a bit-stream image, an exact copy of digital data. 
Enables analysis while preserving the integrity of the original data.

## Page 3

Bit-Stream Image: 
A complete, unchanged copy of data from a digital storage device. 
Captures all data, including file structures and deleted files. 
Used for forensic analysis while preserving the original evidence. 
 
Securing and Preserving Evidence: 
Involves documenting evidence details, including description and location. 
Using proper packaging and labeling for physical evidence. 
Storing evidence in secure, controlled environments. 
Restricting access to authorized personnel and maintaining logs. 
Continuously updating chain of custody records. 
Preserving evidence integrity by protecting it from damage and unauthorized 
access. 
These practices are essential to maintain the integrity and admissibility of evidence 
in legal investigations and proceedings. 
 
8. What is a forensic hash? Why do we need hashing in forensics? 
A forensic hash, also known as a cryptographic hash or simply a hash, is a fixed-
length string of characters generated from the content of a file or data. It's created 
using a hash function, which takes input data and produces a unique, fixed-size 
output (the hash value). Common hash functions include MD5, SHA-1, and SHA-
256. 
 
a. If a single letter of a file changes, would the file hash change? 
Yes, if any part of the file's content changes, including a single letter, the file's hash 
will change. Hash functions are designed to be highly sensitive to even the smallest 
changes in input data. Changing a single character in a file will produce a 
significantly different hash value.

## Page 4

b. If the title of a document changes, would the file hash change? 
No, changing the title or metadata of a document typically does not affect the 
content of the file itself. Hashing is based on the file's content, not its metadata. 
Therefore, the hash value will remain the same as long as the content remains 
unchanged. 
c. If a computer (image) is hashed as part of the acquisition, what would cause the 
hash to change? 
The hash of a computer image (bit-stream image) should not change if the image is 
created correctly, and the content remains unaltered. However, several factors could 
cause the hash to change: Physical damage or corruption of the storage medium. 
Errors in the imaging process. Changes made during the investigation, such as 
adding or modifying files on the image. Differences in acquisition tools or settings 
used at different times.
