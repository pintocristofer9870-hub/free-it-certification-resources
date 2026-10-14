
# IP Subnetting Practice Guide

Learn IPv4 subnetting with simple explanations, worked examples, and practice questions. This guide is useful for networking students and people preparing for entry-level networking certifications.

## Table of Contents

- [What Is Subnetting?](#what-is-subnetting)
- [Understanding CIDR Notation](#understanding-cidr-notation)
- [Common Subnet Masks](#common-subnet-masks)
- [Worked Example](#worked-example)
- [Practice Questions](#practice-questions)
- [Answers and Explanations](#answers-and-explanations)
- [Further Study](#further-study)

## What Is Subnetting?

Subnetting divides an IP network into smaller logical networks called subnets.

It helps network administrators:
- Organize devices into logical groups.
- Use IPv4 address space efficiently.
- Separate network segments.
- Plan routing and network security.

## Understanding CIDR Notation

CIDR stands for Classless Inter-Domain Routing.

An IPv4 address contains 32 bits. In a CIDR prefix such as `/24`, the number after the slash identifies how many bits belong to the network portion.

For example:

`192.168.1.0/24`

- Network bits: 24
- Host bits: 8
- Total addresses: 2^8 = 256
- Traditionally usable host addresses: 254

For a conventional IPv4 subnet, the network and broadcast addresses are not assigned to ordinary hosts.

## Common Subnet Masks

| CIDR | Subnet Mask | Total Addresses | Usable Host Addresses |
|---|---|---:|---:|
| /24 | 255.255.255.0 | 256 | 254 |
| /25 | 255.255.255.128 | 128 | 126 |
| /26 | 255.255.255.192 | 64 | 62 |
| /27 | 255.255.255.224 | 32 | 30 |
| /28 | 255.255.255.240 | 16 | 14 |
| /29 | 255.255.255.248 | 8 | 6 |
| /30 | 255.255.255.252 | 4 | 2 |

These usable-host counts apply to conventional IPv4 subnets, not special cases such as `/31` point-to-point links or `/32` host routes.

## Worked Example

**Question:** Which subnet contains the IP address `192.168.1.70/26`?

### Step 1: Identify the subnet mask

A `/26` prefix corresponds to:

`255.255.255.192`

### Step 2: Calculate the block size

The interesting octet is the last octet.

Block size = 256 - 192 = 64

### Step 3: List the subnet ranges

The subnet ranges in the last octet begin at:

- 0–63
- 64–127
- 128–191
- 192–255

### Step 4: Find the correct range

The address `192.168.1.70` falls within 64–127.

Therefore:

- **Network address:** `192.168.1.64`
- **First usable address:** `192.168.1.65`
- **Last usable address:** `192.168.1.126`
- **Broadcast address:** `192.168.1.127`

The answer is `192.168.1.64/26`.

## Practice Questions

Try answering these questions before checking the solutions.

### Question 1

How many total IPv4 addresses are in a `/27` subnet?

- A. 16
- B. 32
- C. 64
- D. 128

### Question 2

What is the subnet mask for `/28`?

- A. 255.255.255.0
- B. 255.255.255.192
- C. 255.255.255.224
- D. 255.255.255.240

### Question 3

Which network contains `192.168.10.140/26`?

- A. 192.168.10.0/26
- B. 192.168.10.64/26
- C. 192.168.10.128/26
- D. 192.168.10.192/26

### Question 4

How many traditionally usable host addresses are available in a `/29` subnet?

- A. 2
- B. 6
- C. 8
- D. 14

### Question 5

What is the broadcast address of `10.0.5.64/27`?

- A. 10.0.5.63
- B. 10.0.5.95
- C. 10.0.5.96
- D. 10.0.5.127

## Answers and Explanations

**Question 1: B — 32**

A `/27` prefix leaves 5 host bits.

Total addresses = 2^5 = 32.

**Question 2: D — 255.255.255.240**

A `/28` subnet mask has 28 network bits and corresponds to `255.255.255.240`.

**Question 3: C — 192.168.10.128/26**

A `/26` subnet has a block size of 64. The ranges are 0–63, 64–127, 128–191, and 192–255. The address 140 belongs to the third range.

**Question 4: B — 6**

A `/29` subnet contains 8 total addresses. Subtracting the network and broadcast addresses leaves 6 traditionally usable host addresses.

**Question 5: B — 10.0.5.95**

A `/27` subnet has a block size of 32. The subnet beginning at 10.0.5.64 ends at 10.0.5.95, which is its broadcast address.

## Further Study

Consistent practice helps build subnetting speed and accuracy.

Explore additional IT certification preparation resources, practice questions, and study materials at [ExamsTeacher.com](https://examsteacher.com/).

For exam-specific preparation, consult the certification provider's current official exam objectives.

## Disclaimer

This is an independent educational resource. It is not affiliated with or endorsed by Cisco or any other certification provider.

The questions in this guide are original practice exercises, not actual or leaked certification exam questions.

## Contributing

Suggestions and corrections are welcome. Please ensure that contributions are accurate, original, and clearly explained.
