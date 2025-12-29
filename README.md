☁️Azure 3-Tier Architecture Project

📌 Overview
Implemented a 3-Tier Architecture on Microsoft Azure to build a secure and scalable web application by separating Web, Application, and Database layers using Azure networking and security services.

⸻

🧱 Architecture
	•	Web Tier: Nginx (Public VM – Port 80)
	•	App Tier: Apache Tomcat (Private VM – Port 8080)
	•	DB Tier: MySQL (Private VM – Port 3306)

⸻

🛠️ Azure Services Used
	•	Azure Virtual Machines (Linux)
	•	Virtual Networks (VNets) & Subnets
	•	Network Security Groups (NSGs)
	•	VNet Peering

⸻

🔐 Security
	•	Web tier publicly accessible
	•	App & DB tiers isolated in private subnets
	•	NSGs allow only required inter-tier traffic

______

🔄 Request Flow
User → Web Server → App Server → Database

______

🎯 Key Learnings
	•	Multi-tier cloud architecture design
	•	Secure network isolation using Azure NSGs
	•	VNet peering across regions
	•	Real-world Azure deployment experience
