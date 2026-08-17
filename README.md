# aws-lamp-assignment
LAMP website
# AWS LAMP Project Assignment

## Objective
Launch an EC2 instance, host a LAMP project, create a backup image, 
share it, and verify recovery — then clean up all resources.

## Steps Completed

### 1. Launched EC2 instance & hosted LAMP project
Installed Apache, MySQL, PHP on an Ubuntu EC2 instance and deployed a PHP page.
![EC2 instance](<img width="1892" height="830" alt="Screenshot 2026-08-16 230242" src="https://github.com/user-attachments/assets/3c3c1319-eda1-4bd7-95d5-3b83bfc4dded" />
)
![Website live](<img width="1841" height="907" alt="Screenshot 2026-08-16 230327" src="https://github.com/user-attachments/assets/cd89e503-cab6-4b79-9f95-3f0504690de3" />
)

### 2. Created an AMI (image) of the instance
![AMI created](<img width="1762" height="555" alt="Screenshot 2026-08-16 230428" src="https://github.com/user-attachments/assets/4f445532-e685-4c50-8708-01107e8cb9db" />
)

### 3. Shared the image with a friend
![AMI shared]<img width="1847" height="750" alt="Screenshot 2026-08-16 230555" src="https://github.com/user-attachments/assets/8212144c-6f68-4e14-8dee-a05284d77d46" />
()

### 4. Launched backup instance from the image & verified website
![Backup instance running](<img width="1814" height="732" alt="Screenshot 2026-08-16 231051" src="https://github.com/user-attachments/assets/bfa97e92-a022-4b3f-b3b0-bbe24239afd1" />

![Backup website working] <img width="1841" height="751" alt="Screenshot 2026-08-16 230959" src="https://github.com/user-attachments/assets/895c9747-73c9-4e61-adec-12cd416b97dc" />
)

### 5. Deleted all created resources
Terminated instances, deregistered AMI, deleted snapshot to avoid charges.

## Tech Stack
Linux (Ubuntu) · Apache · MySQL · PHP · AWS EC2 · AMI
