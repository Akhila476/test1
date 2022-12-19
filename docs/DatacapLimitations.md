---
layout: default
title: Datacap Scan Limitations
nav_order: 10
---

**Limitation to scan same document**
1. Click on DataCap Main page.
2. Job Monitor page will open.
3. Select the Scan icon, NScan page opens for scanning documents.
4. Click on browse, select the document from the selector window.
5. Select the Process Name from the Drop-Down list.
6. After scanning the document Submit button will be enabled. 
7. When the user scans the document and that gets aborted then, the user should not scan more than 2 times the same document with the same process name.
8. If the user scans the same document which gets aborted multiple times it definitely gets the same status, instead of scanning more than 2 times, users need to inform the PROD Support Team.
9. **If any batch got aborted then either the user needs to inform the PROD Support team or raise a Jira ticket.**

![image](https://media.github.ibm.com/user/376381/files/702f7300-132c-11ed-92f8-47ad15725334)

10. If the previously scanned document failed at Export then there is NO need to Scan the same documents again because we can re-process that failed / aborted Batch once again.
11. If batches were getting aborted and if that count reached up to 3 then kindly don't scan or upload any document further. Because Datacap has inbuilt functionality to Stop processing if batches are aborted more than 3 times.
