# Foundations_of_Cloud_Computing

Foundations of Cloud Computing


| Категорія                   | AWS         | GCP                          |
|-----------------------------|-------------|------------------------------|
| **Compute**                 | EC2         | Compute Engine               |
|                             | Lambda      | Cloud Functions / Cloud Run  |
| **Storage**                 | S3          | Cloud Storage                |
|                             | EFS         | Filestore                    |
| **Database**                | RDS         | Cloud SQL                    |
|                             | DynamoDB    | Firestore / Bigtable         |
|                             | ElastiCache | Memorystore                  |
| **Networking**              | VPC         | VPC                          |
|                             | CloudFront  | Cloud CDN                    |
|                             | Route 53    | Cloud DNS                    |
| **Security**                | IAM         | IAM                          |
|                             | WAF         | Cloud Armor                  |
| **Monitoring & Management** | CloudWatch  | Cloud Monitoring             |
|                             | CloudTrail  | Cloud Audit Logs             |

#



### Порівняння управління користувачами та доступом


**AWS**
- Створюєш IAM User у консолі AWS
- Джерело: AWS акаунт (root) + IAM Users
- Управління: IAM політики, групи, IAM Roles

**GCP**
- Додаєш існуючий Google Account
- Джерело: Google Account / Workspace
- Управління: IAM ролі на рівні проекту/ресурсу

**Azure**
- Створюєш у Azure AD або запрошуєш зовнішніх
- Джерело: Azure AD акаунт / Guest email
- Управління: RBAC ролі на ресурс/групу/підписку

**DigitalOcean**
- Додаєш членів команди через email-запрошення
- Джерело: DigitalOcean акаунт
- Управління: Простий набір ролей: Owner, Member, Billing

#