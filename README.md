# MTA-STS Policy for vspry.com

This repository hosts the **MTA-STS policy file (`mta-sts.txt`)** for vspry.com.  
MTA-STS (Mail Transfer Agent Strict Transport Security) is a security standard that helps enforce encrypted email transport via SMTP.

## 📄 Hosted File
- **File Path**: `.well-known/mta-sts.txt`
- **Live URL**: [`https://mta-sts.vspry.com/.well-known/mta-sts.txt`](https://mta-sts.vspry.com/.well-known/mta-sts.txt)

## 🔄 Updating the Policy
1. Edit the `mta-sts.txt` file in the `.well-known/` directory.
2. Ensure the policy follows the correct format:
   ```txt
   version: STSv1
   mode: enforce
   mx: vspry.com
   max_age: 86400
