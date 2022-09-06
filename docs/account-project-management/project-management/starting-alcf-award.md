# Starting Your ALCF Award

The following guide is for PIs and Proxies to prepare for the start of their INCITE project.

## Get Started with ALCF’s Systems
To get your project up and running, please view our documentation on Theta and ThetaGPU at: https://www.alcf.anl.gov/support-center/theta-and-thetagpu

We also encourage you to take full advantage of ALCF's training programs and user services. Some useful introductory materials and videos are listed below:
- Theta and Cooley Overview : http://bit.ly/Getting_Started_On_Theta
- Running on Theta: https://www.alcf.anl.gov/events/best-practices-queueing-and-running-job…
- ThetaGPU Overview: https://www.youtube.com/watch?v=N0Xip1mUZY8
- Lustre File Striping Basics: https://www.alcf.anl.gov/support-center/training-assets/file-systems-an…
- ACDC (using Eagle): https://www.alcf.anl.gov/support-center/theta-and-thetagpu/eagle-data-s…

## Project Terminology
Before your project begins, you will receive an email with the following project information:
- **Project Short Name**: The assigned, shortened name for your project. This will be the name that you’ll use to access your project on the systems.
- **Project Proxies**: Project members designated by PIs that are authorized to add or renew project members on your behalf.
- **Allocation System(s) and Allocation Amount**: The approved system(s) and amount of your award in node hours.
- **Approved Quota**: The approved amount of disk space for your project directory.
- **File System**: The file system where your project directory will reside. For information on the Grand and Eagle file systems, see Storage and Networking.
- **Assigned Catalyst**: INCITE projects will have ALCF staff members that are assigned to the projects who are available to assist the team throughout the duration of the INCITE allocation.
- **Allocation Start Date**: The start date of your award.
- **Allocation End Date**: The end date of your award.

Once your project has been created, you can view and manage your project details. See Managing Your Team Members.

## Project Status Reports
After your allocation begins, you will receive a weekly project status report via support@alcf.anl.gov.

**Example subject for email**: ALCF INCITE-2022 Project Status Report for [PROJECT SHORT NAME]

## Reporting Requirements
Projects are required to submit quarterly reports to inform DOE of your INCITE 2022 progress. We will send you a report template at the end of each quarter.

Please complete the report promptly and submit it via email to support@alcf.anl.gov. For due dates and penalties, see INCITE Quarterly Report Policy.

## Account Setup
If you do not have an ALCF account, you will need to request one at https://accounts.alcf.anl.gov/accountRequest.  When prompted for project name, please select the INCITE project name.

If you have an active ALCF account, submit a request to join the INCITE project at https://accounts.alcf.anl.gov/#!/joinProject

## User Agreement
If you are not an employee of Argonne National Laboratory, a user agreement must be signed by your home institution to perform research at Argonne’s user facilities. This policy applies to every member of the project team who will be conducting research on ALCF resources.

A list of home institutions that have master agreements in place is located on this webpage:  https://www.aps.anl.gov/Users-Information/Legal-Financial/Argonne-User-…

### ALCF Acknowledgement Form
Every project team member who requests an ALCF account must sign and return an acknowledgment form, stating that they agree to the terms in the user agreement.

The form is located at: https://www.alcf.anl.gov/files/Acknowledgement_Form.pdf. Please print, sign, scan and email it to accounts@alcf.anl.gov.

### Foreign National Access Request Form
The U.S. Department of Energy has guidelines and requirements for foreign visitors who access its facilities and sites. This guidance is issued in DOE Order 142.3, which is part of Argonne's contract; therefore, all foreign visitors (non-U.S. Citizens) must obtain authorization prior to using ALCF resources.

If you are a foreign national and do not have current authorization credentials, you will require an ANL-593 (Foreign National Access Request) form. It is critical that documentation requests sent by ALCF staff are completed as early as possible to facilitate timely processing for your account approval.

## Managing Project Team Membership
As a PI, you can add members to your project. You can assign proxies who are project members authorized to add or renew project members on your behalf.

A project PI or proxy has the authority to:
- Approve and renew accounts.
- Add and delete users to/from the project.
- Approve Foreign Assignment/Visit Request form renewals for project members who are foreign nationals.

During your project setup, the ALCF Support Team will request the following information to establish your project members:
- The names, email addresses, and/or ALCF usernames (if already existing) of up to two proxies and all project members.

### Adding Project Members
The PI or a proxy must approve each team member to access ALCF resources and run jobs on their project. PI/proxies can respond to emails from ALCF for account access approval with a "yes" or "no".

PI/proxies with active ALCF accounts can also approve new account requests, project membership requests, account reactivation requests, add existing active ALCF users to the project by logging into the ALCF Account and Project Management application.  

**Note:** If PI/proxies need to request an ALCF account, see the section below for instructions on "how to apply" for an account.

### Accounts and Access for your Project Members
All project members will need an ALCF user account to access project data and to run jobs on ALCF systems.

Members that do not have an ALCF account should request one at: https://accounts.alcf.anl.gov/accountRequest. When prompted for project name, they should select your project short name.

If your project members have ALCF accounts that are no longer active, please ask them to submit a reactivation request here: https://accounts.alcf.anl.gov/accountReactivate. When prompted for project name, they should select your project short name.

If you project members have active ALCF accounts but have not been added to your project, they should submit a request to join your project by going to this page : https://accounts.alcf.anl.gov/#!/joinProject

## Moving Your Data
We encourage you to use Globus to move your project data to your ALCF project directory before your allocation begins. For details, see Using Globus on Theta.

## Policies
### Pullback Policy
Please be aware that we will periodically monitor, and could potentially adjust, your project allocation if a large portion of it goes unused. You may view our pullback policy at the following link: https://www.alcf.anl.gov/user-guides/pullback-policy

### Allocation Overburn Policy
Please see this page for overburn/overuse eligibility for INCITE projects that have exhausted their allocation in the first 11 months of its allocation year: https://www.alcf.anl.gov/support-center/facility-policies/queue-and-sch…

### Acknowledgment In Publications
Please follow the guidelines provided at https://www.alcf.anl.gov/user-guides/alcf-acknowledgement-policy to properly acknowledge the use of ALCF resources in all of your publications, both online and print.

### Facility Policies
Facility policies have been established to provide consistent and reliable services. Please read at: https://www.alcf.anl.gov/user-guides/policies

## Useful Allocation and Quota Commands
We have an allocation management tool called sbank, and below are a few helpful sbank commands.  
- myprojectquotas: log into Theta and type this command to view the project directory quotas for all your projects
- myquota: log into Theta and type this command to view your home directory quota

You can use the following command to check your project balance on Theta:
- sbank-list-allocations -p <Project Shortname> -r <system name>

For more command examples and details, see [sbank](#).

## How Can We Help?
We can also help resolve any issues or needs that may be delaying the start of your scientific campaign.
- Are you in need of high-throughput software?
- Are you having difficulty compiling your application?
- Does your code have limited restart capabilities?
  
If your project allocation usage is being held back for reasons due to one of our systems, please contact us for assistance by emailing [support@alcf.anl.gov](support@alcf.anl.gov).
  
  