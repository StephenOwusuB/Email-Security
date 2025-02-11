# Email Security

## Table of Contents
- [Objectives](#objectives)
- [Languages and Utilities](#languages-and-utilities-used)
- [Environment](#environment)
- [Project Walk-Through](#project-walk-through)
- [Skills Learned](#skills-learned)
- [Acknowledgments](#acknowledgments)

## Objectives

In this project, we will set up a Business 365 email in Microsoft. This hands-on lab aims to enhance our understanding of setting up and securing an organization's email environment by implementing SPF, DKIM, and DMARC. Configuring and managing this lab has significantly contributed to my knowledge of maintaining a cloud-based email environment.

## Languages and Utilities Used

- **Git**: For version control and collaboration.
- **Visual Studio Code**: As the primary code editor for writing and managing scripts.
- **Markdown**: For creating detailed documentation and guides.

## Environment

To set up a business email environment and secure the business email, you will need the following components:

- **Microsoft business standard account**  
    - Sign up for a free Microsoft Business Account for 30 days [Microsoft Business Trial](https://www.microsoft.com/en-us/microsoft-365/business/microsoft-365-business-standard-one-month-trial).
    - Assign Microsoft Business Standard license to a user.

- **Custom Domain from Namecheap**  
    - Purchase a custom domain from [Namecheap](https://www.namecheap.com/).

- **MXTOOLBOX**  
    - Check for SPF and DMARC on [MXToolbox](https://mxtoolbox.com/).

## Project Walk-Through

1. **Enroll in Microsoft 365 Business Standard for a complimentary 30-day trial.**  
    ![M365 Free](images/M365%20free.jpg)

2. **Add Microsoft Business Standard license to a user.**  
    ![Assign License](images/assign%20m365%20business%20standard.png)

3. **Navigate to the Microsoft Admin Center and choose the 'Setup' option.**  
    ![Microsoft Admin Center](images/click%20on%20setup.jpg)

4. **Select "Get your custom domain set up".**  
    ![Custom Domain](images/select%20get%20your%20custom%20domain%20setup.jpg)

5. **Click on 'Get Started' to add your custom domain.**  
    ![Setup Custom Domain](images/setup%20custom%20domain%20for%20mail.png)

6. **If your custom domain is not visible, select 'Add Domain' to integrate it.**  
    ![Add Domain](images/click%20on%20add%20domain.png)

7. **Choose your preferred method for connecting your domain.**  
    ![Add Domain to Email](images/add%20domain%20to%20your%20email%20setup.png)

8. **Copy the three records (MX, TXT, and CNAME) and add them to your domain registrar.**  
    ![Add DNS Records](images/add%20dns%20records%20in%20365.png)

9. **Refresh the page, and you should see the domain status change to 'Healthy'.**  
    ![Health Status](images/health%20status%20green%20check.png)

10. **Verify SPF Setup**: Open [MXToolbox](https://mxtoolbox.com), change the search type to 'SPF Lookup', and enter your domain.  
    ![Verify SPF](images/verify%20spf%20was%20setup%20successfully%20.png)

11. **Proceed to set up DKIM**.  
    ![DKIM Setup](images/click%20on%20security%20for%20DKIM.png)

12. **Create DKIM keys and add CNAME records to your domain registrar.**  
    ![Create DKIM Keys](images/create%20DKIM%20keys.png)

13. **Enable DKIM signing.**  
    ![Enable DKIM](images/successful%20enabled%20sign%20messages.png)

14. **Configure DMARC**: Create a TXT record in your domain registrar and monitor the email system for any issues.  
    ![DMARC Success](images/successful%20email%20received.png)

## Skills Learned

- **Email Security Configuration**: Gained hands-on experience in setting up SPF, DKIM, and DMARC to secure an organization's email environment.
- **Domain Management**: Learned how to manage custom domains within Microsoft 365 and navigate domain registrars.
- **Technical Documentation**: Developed the ability to create clear and professional documentation for technical processes and configurations.
- **Problem-Solving**: Enhanced problem-solving skills by troubleshooting and resolving issues related to domain verification and email authentication.
- **Cloud-Based Email Administration**: Improved knowledge of administering and maintaining a cloud-based email environment.

## Acknowledgments

Special thanks to all contributors and the community for their support and guidance. This project was inspired by various resources and projects in the cybersecurity and IT fields.

