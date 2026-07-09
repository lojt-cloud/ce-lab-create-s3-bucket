# Create S3 Bucket Lab - Solution

**Student Name: Balint Lojt
**Date: 09/07/2026

---

## Exercise 1: Bucket Creation

**Bucket Name:** [balint-lojt-bootcamp-demo-2024]  
**Region:** [us-east-1]

<img width="1860" height="770" alt="bucket-created" src="https://github.com/user-attachments/assets/419f7564-352e-4dc1-aeec-d61ca4b24d1f" />


---

## Exercise 2: Object Uploads

### Files Uploaded:
1. sage.jpg
2. README.txt
3. Balint_Lojt_CV_teach.pdf

### Folder Structure:
<img width="854" height="165" alt="folder-structure" src="https://github.com/user-attachments/assets/3a49d46b-fdb6-45db-a252-45581d148d82" />


**Folders Created:**
- images/
- documents/
- backups/

<img width="1110" height="514" alt="files-uploaded" src="https://github.com/user-attachments/assets/7b16ed88-e752-4f8a-91b3-eb0b339f7c1c" />


---

## Exercise 3: Storage Classes

![Storage Classes](screenshots/storage-classes.png)

**Storage Classes Used:**
- Standard: [Number] objects
- Standard-IA: [Number] objects
- Intelligent-Tiering: [Number] objects

---

## Exercise 4: Bucket Features

### Versioning:
![Versioning Enabled](screenshots/versioning-enabled.png)
![Versions List](screenshots/versions.png)

**Number of versions created:** [X]

### Encryption:
![Encryption Enabled](screenshots/encryption-enabled.png)

**Encryption type:** SSE-S3

### Tags:
![Tags](screenshots/tags.png)

**Tags Added:**
- Environment: Development
- Project: Bootcamp

---

## Exercise 5: Download/Delete

**Operations Completed:**
- [x] Downloaded object via console
- [x] Downloaded object via CLI
- [x] Deleted object via console
- [x] Deleted object via CLI

---

## Exercise 6: Sync Operations

![Synced Files](screenshots/synced-files.png)

**Files Synced:** [Number]  
**Total Size:** [Size]

---

## Exercise 7: Metrics

![Bucket Metrics](screenshots/bucket-metrics.png)

**Bucket Statistics:**
- Total objects: [X]
- Total size: [X GB]
- Storage class distribution: [Details]

---

## Bonus Challenges

### Lifecycle Policy:
![Lifecycle Policy](screenshots/lifecycle-policy.png)

**Policy Rules:**
- [x] Transition to Standard-IA: 30 days
- [x] Transition to Glacier: 90 days
- [x] Delete: 365 days

---

## CLI Outputs

See `cli-outputs.txt` for all command outputs.

---

## Reflection

**What did you learn about S3?**
[Your answer]

**When would you use different storage classes?**
[Your answer]

---

## Checklist

- [ ] Bucket created
- [ ] Objects uploaded (console and CLI)
- [ ] Folders created
- [ ] Storage classes configured
- [ ] Versioning enabled and tested
- [ ] Encryption enabled
- [ ] Tags added
- [ ] Sync completed
- [ ] All screenshots captured
- [ ] Bucket cleaned up (deleted)

**Completed By:** [Your Name]
