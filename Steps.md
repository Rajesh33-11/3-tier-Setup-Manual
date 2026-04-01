# Create VPC
- Go to AWS Console
- Search → VPC
<img width="1695" height="885" alt="image" src="https://github.com/user-attachments/assets/c790f562-f4df-45c2-b61c-96d32debb5e5" />
- Click → Create VPC
<img width="1910" height="883" alt="image" src="https://github.com/user-attachments/assets/c3be858f-12d9-48e6-b2c9-39c7d115b012" />
- Select:
✅ VPC only
<img width="1487" height="436" alt="image" src="https://github.com/user-attachments/assets/7ae61848-03ba-465d-8b21-909fdf2a510c" />

- Fill details: **Name: vpc-project  →  CIDR: 20.0.0.0/16  →  Click → Create VPC**
<img width="953" height="693" alt="image" src="https://github.com/user-attachments/assets/002e2761-ff3c-4d95-95b9-8c55d619cae4" />
<img width="1934" height="496" alt="image" src="https://github.com/user-attachments/assets/0b3b261c-3b29-4571-ae51-94e80fdc4170" />

-----
## 🔹 Step 4: Create Internet Gateway (IGW)
Left side → Internet Gateways
<img width="947" height="770" alt="image" src="https://github.com/user-attachments/assets/018266f8-7096-4966-8f35-848b09d1e266" />
Click → Create Internet Gateway
<img width="1648" height="434" alt="image" src="https://github.com/user-attachments/assets/39c2cef5-0270-49ea-8078-266314cff9e5" />
Name: my-igw
Click → Create
<img width="1807" height="661" alt="image" src="https://github.com/user-attachments/assets/08987db6-0c35-43fe-b67e-3d2316127fa6" />
<img width="1611" height="297" alt="image" src="https://github.com/user-attachments/assets/a9b841cd-5502-4b08-b774-14476d1afa80" />
## Attach IGW:
Select IGW
<img width="1601" height="275" alt="image" src="https://github.com/user-attachments/assets/2e723b76-98e4-4d08-a00e-7813ef1aaa4b" />
Click → Actions → Attach to VPC
<img width="1605" height="472" alt="image" src="https://github.com/user-attachments/assets/fc176ab5-5e57-4683-9bcb-187f8a9053a1" />
Choose my-vpc
<img width="1845" height="448" alt="image" src="https://github.com/user-attachments/assets/91909c95-95ce-4f43-b9cb-28f566566d44" />
<img width="1603" height="389" alt="image" src="https://github.com/user-attachments/assets/096ce8fa-8388-4104-989c-c06dc0c0ffcf" />

