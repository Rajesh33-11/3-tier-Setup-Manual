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
## Create Internet Gateway (IGW)
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
<img width="1817" height="530" alt="image" src="https://github.com/user-attachments/assets/d330a00c-1c7e-444a-a9e0-d16d0f594050" />
<img width="1909" height="321" alt="image" src="https://github.com/user-attachments/assets/e6ba71d3-258b-48d7-b2f6-f6d9392ce22b" />

--------
## Create Public Subnet (2)
- Left side → Subnets
<img width="1042" height="596" alt="image" src="https://github.com/user-attachments/assets/489fc30a-24bb-4d92-b0a3-a08952ea63f9" />
- Click → Create subnet
<img width="1643" height="337" alt="image" src="https://github.com/user-attachments/assets/5fc65a7d-c514-43c7-9368-a61ffb2aa27d" />
- Select your VPC
- <img width="1533" height="422" alt="image" src="https://github.com/user-attachments/assets/1e5ed63e-94ec-46ae-9b74-35729fe5d3d0" 
     
- Enter: **Name: public-subnet  →  AZ: ap-south-1a  →   CIDR: 120.0.1.0/24 →  Click → Create subnet**
<img width="1595" height="772" alt="image" src="https://github.com/user-attachments/assets/60085e55-4835-4161-bf66-af655c0af8ac" />
<img width="1588" height="413" alt="image" src="https://github.com/user-attachments/assets/3ffd22fd-2b7e-43f0-a46d-ed2a1343fe2d" />
