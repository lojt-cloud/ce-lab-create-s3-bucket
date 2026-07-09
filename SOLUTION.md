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

<img width="2079" height="689" alt="storage-classes" src="https://github.com/user-attachments/assets/a6c7843d-0564-455f-88b7-760f56753cfb" />


**Storage Classes Used:**
- Standard: 1 object
- Standard-IA: 1 object
- Intelligent-Tiering: 1 object

---

## Exercise 4: Bucket Features

### Versioning:
<img width="1815" height="351" alt="versioning-enabled" src="https://github.com/user-attachments/assets/f9f78935-f03a-47ca-801e-3b4a0202ad1a" />

<img width="1822" height="383" alt="versions" src="https://github.com/user-attachments/assets/8a29bd55-4451-44ad-b9fb-716f80dd0cf2" />


**Number of versions created: 2

### Encryption:
<img width="2518" height="681" alt="encryption-enabled" src="https://github.com/user-attachments/assets/3f0c49cc-e0a6-4ff5-a265-598585529137" />


**Encryption type: SSE-S3

### Tags:
<img width="1654" height="465" alt="tags" src="https://github.com/user-attachments/assets/94ed49d3-c3b7-4f5a-ab65-64494fe3a4bf" />


**Tags Added:
- Environment: Development
- Project: Bootcamp

---

## Exercise 5: Download/Delete

**Operations Completed:**

- [x] Downloaded object via console
- [x] Downloaded object via CLI
- [x] Deleted object via console
- [x] Deleted object via CLI



## Exercise 6: Sync Operations

<img width="980" height="152" alt="synced-files" src="https://github.com/user-attachments/assets/48da45a1-79d4-4f05-b3c2-bbe0f0e981b3" />
<img width="944" height="77" alt="synced-files-modify" src="https://github.com/user-attachments/assets/7a58a888-c3be-41de-a31f-acb9cb978379" />



**Files Synced: 3 
**Total Size: 73

---

## Exercise 7: Metrics

<img width="656" height="257" alt="bucket-metrics" src="https://github.com/user-attachments/assets/42e31215-4ade-4676-ac97-aab99aab8cd2" />


**Bucket Statistics:**
- Total objects: 6
- Total size: 0.004 GB
- Storage class distribution: Standard storage
No metrics available since it hasn't reached the 24 hour time limit to create one.

## Bonus Challenges

### Lifecycle Policy:
![Lifecycle Policy](screenshots/lifecycle-policy.png)

**Policy Rules:**
- [] Transition to Standard-IA: 30 days
- [] Transition to Glacier: 90 days
- [] Delete: 365 days



## CLI Outputs

See `cli-outputs.txt` for all command outputs.
N/A


## Reflection

**What did you learn about S3?**
S3 buckets can be customised using both the CLI and the console, which makes managing them flexible. I can change their properties to do things like add encryption for security, switch the storage tier depending on how frequently the files are being accessed, and turn on versioning to track file history. Also, I found that the sync function helps a lot when you need to quickly create backups for local projects.

**When would you use different storage classes?**
It all depends on how frequently the data is accessed, so you can put files into different classes to keep things cost-efficient. For example, I’d keep active daily files in Standard since it’s fast and has no retrieval fees. But for older backups or documents I only need to look at once a month, I'd use Standard Infrequent Access to cut costs. If I have compliance data or legal backups that I rarely look at, I'd put them into Glacier because the storage is cheap. If I'm not totally sure how often data will be used, Intelligent-Tiering automatically shifts things around for me to save money.

---

## Checklist

- [x] Bucket created
- [x] Objects uploaded (console and CLI)
- [x] Folders created
- [x] Storage classes configured
- [x] Versioning enabled and tested
- [x] Encryption enabled
- [x] Tags added
- [x] Sync completed
- [x] All screenshots captured
- [x] Bucket cleaned up (deleted)

**Completed By: Balint Lojt
