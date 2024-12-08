# Stanislav Hehera

Rust software engineer

## Contact

- Email: grenwood27sg@gmail.com
- GitHub: https://github.com/Silverhorn27
- LinkedIn: https://www.linkedin.com/in/stas-hehera-9782b1183/

## Profile

Software engineer with 4 years of startup experience.

## Skills

- Linux, Windows
- AWS
- PL: Rust, C++, bash, Python, PowerShell
- filesystems (ext4, ntfs), nbd, AWS EFS
- CI/CD: GitHub actions
- git

## Work Experience

### Rust Development — Elastio (2020–2024)

[Elastio](https://elastio.com) is a startup that provides data backup, recovery, and malware/ransomware detection solution for AWS cloud. Elastio is an AWS Security and Storage Competency Partner.

- As a member of the ‘data plane’ team, I wrote Rust code for mounting network block devices, creating backups of AWS assets (EBS, EC2, AMI), and data recovery. (This predates the AWS Backup service.)
- I programmed the integration of the Elastio platform with AWS Backup **in a month**. Subsequently, I developed a solution for scanning recovery points stored in AWS's regular and logically air-gapped (LAG) vaults, ensuring enhanced data protection against malware and ransomware.
- As a member of the ‘anti-ransomware’ team, I developed and maintained Elastio's crown jewel — `iscan` — the software for ransomware and malware detection.
- I achieved a **5x** speed improvement in scanning files on EXT4 file systems by analyzing their raw structure. By writing code to directly access the filesystem, I located and cached metadata ranges of all files, significantly enhancing scanning efficiency.
- Optimized performance of network block devices I/O, improving throughput and reliability.

## Open Source

Contributed code patches to [`libparted`](https://github.com/pop-os/libparted/pull/10) and [`blkid`](https://github.com/cholcombe973/blkid/pull/10) Rust libraries.

## Education

### National University of Life and Environmental Sciences of Ukraine, Kyiv, Ukraine, 2020-2023

- Bachelor's degree: Software engineering

### Novovolynsk Electromechanical College, Novovolynsk, Ukraine, 2016-2020
- Junior specialist: Maintenance of computer systems and networks (Honors)
