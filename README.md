# Active-Directory-and-User-Management-Lab

## The Environment Architecture

<img width="958" height="500" alt="Screenshot 2026-09-28 223145" src="https://github.com/user-attachments/assets/096e13a1-581e-4f4d-a958-cbe2110c9fa1" /> <img width="958" height="500" alt="Screenshot 2026-09-28 223209" src="https://github.com/user-attachments/assets/790e7238-f748-4a9b-825d-7065798c0105" />
Building the foundation: VMware Workstation inventory pane displaying both the Windows Server 2022 Domain Controller and Windows 11 client VMs running concurrently

<img width="958" height="500" alt="Screenshot 2026-09-28 224216" src="https://github.com/user-attachments/assets/60175d6f-e917-46e2-b0ca-8271c69771f3" />
Configuring an isolated Host-only network (VMnet1) within the VMware Virtual Network Editor to ensure secure, private communication for the domain environment.

## Corporate Structure (Organizational Units)

<img width="1917" height="1020" alt="Screenshot 2026-09-28 230625" src="https://github.com/user-attachments/assets/ed3dec2f-a7f6-4b73-8f1d-a0ebc0ef2db6" />
Designing a scalable corporate hierarchy using Organizational Units (OUs) mapped to standard business departments.

## User & Group Provisioning

<img width="1917" height="1020" alt="Screenshot 2026-09-28 230228" src="https://github.com/user-attachments/assets/6c36307d-c96f-429d-a449-d8551aec5b19" />
Populating departmental OUs with standardized user accounts, complete with consistent naming conventions and profile metadata.

<img width="1917" height="1018" alt="Screenshot 2026-09-28 230805" src="https://github.com/user-attachments/assets/ae509872-496e-4a81-99eb-64d1fe02cb92" />
Implementing Role-Based Access Control (RBAC) by nesting specific users into departmental security groups.

## Group Policy Objects (GPOs)

<img width="1917" height="1023" alt="Screenshot 2026-09-28 230955" src="https://github.com/user-attachments/assets/7836e4a7-fd66-4093-aa78-c160a42d0ab4" />
Enforcing corporate security standards by linking custom Group Policy Objects (GPOs) directly to targeted departmental OUs.

<img width="1916" height="1022" alt="Screenshot 2026-09-28 231117" src="https://github.com/user-attachments/assets/04cd662e-1f44-4d12-a79d-935d7fefc4d5" />
Deep dive into policy configuration: Enforcing a mandatory 15-minute idle screen lockout across all domain workstations.

## Client Machine Domain Join

<img width="1917" height="1020" alt="Screenshot 2026-09-28 231207" src="https://github.com/user-attachments/assets/c3e2815e-dd2b-4e5f-ace7-188d01b092b8" />
The successful handshake: Windows 10 client machine officially authenticated and joined to the local corporate domain.

<img width="1917" height="1026" alt="Screenshot 2026-09-28 231419" src="https://github.com/user-attachments/assets/85dd84ea-df3f-446a-805c-d976be5adbf1" />
End-to-end validation: Authenticating a standard domain user on the client workstation via Active Directory credentials.


