---
layout: page-with-toc
title: "Portfolio: Fiksu"
subtitle: Building to scale.
ordered: true
permalink: "/portfolio/fiksu"
redirect_from:

---
# Introduction 
Fiksu was a mobile advertising technology company that helped brands reach their marketing goals in the mobile space.

# Team
I joined Fiksu in 2012 as the first full-time hire for IT. I managed contract support resources as I learned the technology and business environment. As the company started to scale, I made a case to build out an in-house team and built out IT Operations and Business Systems teams. When Fiksu was at its headcount apex of around 350 people, my IT Operations team was three people and my business operations team was two people.

# Major Accomplishments
Here are some of my major accomplishments while at Fiksu. I focus on my specific contributions, but in every case worked with a number of other fantastic people, especially the managers and individual contributors on my team. Please reach out if you'd like to talk about any of these contributions in more detail.    

## Office Expansions
* **When:** 2012-2015
* **Context:** As Fiksu grew and started to build more relationships with brands around the world, we built-out offices to support different geographics, time-zone, and language demands. Our HQ was in Boston, but we opened offices in Northampton, MA; San Francisco, London, Helsinki, Tokyo, and Seoul.
* **What I did:** My team and I coordinated with local heads of offices to deploy security appliances, wireless access points, internet access, and videoconferencing hardware in each office to support each office's needs.

* **Impact:**
  * 📈️️ **Enabled** secure expansion of offices around the world with the technology resources offices needed to be successful.

## Information Security Policy Development
* **When:** 2014
* **Context:** As we started to work with more enterprise-oriented clients, it became essential to have commerically reasonable security policies to ensure that our practices were consistent and industry standard. 
* **What I did:** I researched how to write security policies, using examples from around the internet and tailoring them for Fiksu's environment. I consulted with technical and business leaders to ensure that they would meet both technical and business needs.

* **Impact:**
  * ⬆️️ **Improved** security posture by creating policies and standards around both information and information systems that both IT and Engineering could use to drive decision-making around technical implementations for security matters

## Full Disk Encryption Roll-Out
* **When:** 2013
* **Context:** In a time when full disk encryption was not enabled by default, one of my jobs was to encrypt the hard drives of our entire fleet and ensure that newly deployed devices would be encrypted in the future.
* **What I did:** My team and I built automations to enable full-disk encryption on all newly deployed laptops through our DeployStudio lite-imaging process. For any machines that could not be encrypted remotely, we set up appointments with individual users to complete the process. The entire process was completed with an institutional recovery key so that IT could decrypt any hard-drive, even if the user left the company on less than amicable terms and the admin account wasn't available.

* **Impact:**
  * ⬆️️ **Improved** security posture by ensuring that all endpoints were encrypted in case of loss or theft
  * ⬇️️ **Decreased** time to complete this task by automating it 

## Endpoint Management Software
* **When:** 2013
* **Context:** One of my goals was to improve our security posture and user experience through improved endpoint management. As an early-stage startup, IT had a very modest budget, so I needed a solution that wouldn't cost additional money.
* **What I did:** I used Google's open source [Simian](https://github.com/googlearchive/simian), which extended Disney's open source [Munki](https://www.munki.org/munki/) and enabled easy(ish) hosting in Google Cloud Platform for mere dollars a month. This allowed me to manage macOS System updates on IT-only, beta tester, and production update channels to sufficiently test new macOS updates before deploying them to the entire company. It also allowed me to ensure that core third-party software (e.g., Chrome, Box Sync Client, Firefox) was up-to-date. Additionally, I coupled this with DeployStudio, which allowed me to create a NetBoot based imaging process where I could image new computers with a basic image and then allow Simian to install the latest software. This reduced the time to deploy new equipment or re-image used machines for re-deployment.

* **Impact:**
  * ⬇️️ **Decreased** time spent to image and re-image macOS endpoints for new hires.
  * ⬇️️ **Decreased** time spent to manage third-party software on macOS endpoints.
  * ⬆️️ **Improved** security posture by ensuring that the most frequently used software was updated to the newest version.
  * 💖 **Improved** user experience by giving users the option of when to apply updates that required restarting an application or the entire computer (with a due-date!)

## Office Move
* **When:** 2014
* **Context:** Due to rapid growth, Fiksu moved offices to find a bigger space.
* **What I did:** Once the new space was selected, I planned, coordinated, and executed the movement of IT equipment and services to the new space with my team. This included planning and building out wired and wireless networking services and coordinating with contractors for appropriate cabling as well as installation of a new security appliance, switching stack, and wireless access points as well as Lifesize videoconferencing units. Also worked with a physical security contractor to install a Brivo cloud-based access management system to manage physical access to and within the office.

* **Impact:**
  * ✅️ **Successfully** brought critical services online before employees moved into the new office space.
  * ⬆️️ **Increased** security posture by moving to card-based, logged physical access control

## Videoconferencing Solutions
* **When:** 2013
* **Context:** In its early days, Fiksu operated offices in both Boston, MA and Northampton, MA to attract and retain talent from the Five Colleges. While Northampton, MA employees would travel to Boston frequently to work in-person with other team members, they needed an improved videoconferencing solution for when they needed to join meetings between offices.
* **What I did:** Due to budget constraints, we purchased second-hand Lifesize videoconferencing units and set them up in dedicated rooms in both Northampton and Boston. We successfully configured high-quality feeds between offices. Later, we demoed and onboarded a cloud-based videoconferencing service that would allow participants to join by either the high-quality, dedicated room units or directly from their laptops in the case that they needed to join remotely while travelling or while at home.

* **Impact:**
  * ✅️ **Successfully** implemented a videoconferencing solution to enable improved collaboration between offices and enable more effective remote work.
  * ✅️️ **Successfully** implemented a high-quality solution on a shoestring budget, appropriate for the stage of the start-up.

## Identity Provider as a Service IdPaaS Roll-Out
* **When:** 2012
* **Context:** As a cloud-first software company, Fiksu had a considerable number of cloud applications. My manager and I wanted to achieve a number of goals by implementing a cloud-first IdPaaS: 1) decrease low-value, manual work for IT, 2) improve our security posture through decreasing our attack surface area, and 3) improve user experience by implementing single sign-on.
* **What I did:** I researched and compared vendors, finding the best fit for the company at the time. I worked with teams across the company to move applications behind true SAML or Open ID based SSO or to store shared passwords that couldn't be avoided (due to either technical or business contstraints) in the services password vaulting service.
* **Impact:**
  * ⬆️️ **Improved** user experience by limiting the number of credentials individuals needed to remember
  * ⬇️️ **Decreased** attack surface by removing password based logins wherever possible
  * ⬇️️ **Decreased** low-value, time-consuming work for IT by automating provisioning and deprovisioning activities

## Dropbox to Box Migration
* **When:** 2012
* **Context:** Fiksu had used Dropbox for its first few years due to ease of use and the economics. However, there were insufficient product features at the time to prevent users from accidentally (and permanently) deleting large swaths of data, which had a negative impact on the business. We selected Box, which was more business focused product with more appropriate controls to prevent accidents and limit access based on job role.
* **What I did:** I worked with teams to plan and execute the transfer of data from Dropbox to Box. To make things easier on teams, I performed the migration of shared folders myself using a service machine. I also developed a python script to remove any unsafe characters in filenames that might have been valid for Dropbox but weren't valid for Box.
* **Impact:**
  * ⬇️ **Decreased** incidences of accidental file deletion
  * ⬇️ **Decreased** time to recover files in case of accidental deletion
  * ⬆️️ **Increased** security posture by moving to a service with better logging and granular permissions


# Footnotes
[^1]: [https://en.wikipedia.org/wiki/MicroMasters](https://en.wikipedia.org/wiki/MicroMasters)
[^2]: [https://en.wikipedia.org/wiki/EdX](https://en.wikipedia.org/wiki/EdX)
[^3]: [https://techcrunch.com/2021/06/29/2u-set-to-acquire-non-profit-edx-for-deal-north-of-600m](https://techcrunch.com/2021/06/29/2u-set-to-acquire-non-profit-edx-for-deal-north-of-600m)