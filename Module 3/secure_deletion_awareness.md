# Secure File Deletion Awareness

## 1. What I Learned

Ordinary file deletion does not necessarily erase the underlying data. Secure data sanitization uses methods intended to make stored information unrecoverable.

The appropriate method depends on the storage medium, device capabilities, and security requirements.

## 2. Why It Matters

Understanding deletion and sanitization helps protect sensitive information when disposing of devices or handling confidential files.

## 3. Practical Exploration

* Created `secure_deletion_awareness.py`.
* Explained ordinary deletion and data sanitization.
* Explored SSD-specific limitations.
* Reviewed the role of encryption in protecting stored data.
* Used a read-only educational script without deleting or overwriting files.

## 4. Key Takeaway

* Ordinary deletion does not guarantee secure erasure.
* Individual-file overwriting may be unreliable on SSDs.
* Device-supported sanitization methods may be more appropriate.
* Encryption-based sanitization depends on correct implementation and secure key destruction.
* Always protect important data before sanitizing a device.

## 5. Tools / Concepts Used

* Python
* File systems
* Secure deletion awareness
* SSD storage
* Data sanitization
* Encryption

## 6. Git Commit Note

Add a Python utility explaining secure file deletion concepts.
