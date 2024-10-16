<script setup>
import JobItem from "./JobItem.vue";
import EducationSection from "./EducationSection.vue";
import CommandIcon from "./icons/IconCommand.vue";
import EducationIcon from "./icons/IconEducation.vue";
</script>

<template>
  <JobItem>
    <template #icon>
      <CommandIcon />
    </template>
    <template #heading>Product Developer</template>
    <template #company>Vinetegrate | Jupiter, FL (remote) | April 2024 to September 2024</template>

    <ul>
      <li>Developed new features and improved application performance for both backend and
        frontend code.
      </li>
      <li>Collaborated with a cross-functional team to identify bugs and
        develop new features.
      </li>
      <li>Integrated Twilio, SendGrid, and Filevine APIs to enhance
        functionality.
      </li>
      <li>
        Proposed product and technology improvements to better serve
        customers.
      </li>
      <li>
        Upgraded the code base to Laravel 11 and PHP 8.3 from Laravel 8.8.
      </li>
    </ul>
  </JobItem>

  <JobItem>
    <template #icon>
      <CommandIcon />
    </template>
    <template #heading>Software Engineer</template>
    <template #company>Updater | New York, NY (remote) | April 2022 to December 2023</template>
    <ul>
      <li>
        Maintained and enhanced the MoveHQ SaaS application as part of a cross-functional agile scrum team.
      </li>
      <li>
        Used Jira and GitHub to keep track of issues and updates to code.
      </li>
      <li>
        Created code builds for QA and production through CI/CD pipeline.
      </li>
      <li>
        Developed backend features using PHP/Laravel and frontend interfaces using jQuery and Vue.js.
      </li>
      <li>
        Used docker for local development and testing environments.
      </li>
    </ul>

  </JobItem>

  <JobItem>
    <template #icon>
      <CommandIcon />
    </template>
    <template #heading>Senior Developer</template>
    <template #company>PC Processing | Atlanta, GA | July 2021 to February 2022</template>
    <ul>
      <li>
        Developed an application for the insurance industry to create detailed quotes for various products.
      </li>
      <li>
        Used the Laravel PHP framework together with Vue.js to deliver a responsive and scalable application.
      </li>
    </ul>
  </JobItem>

  <JobItem>
    <template #icon>
      <CommandIcon />
    </template>
    <template #heading>Web Developer and Security Analyst</template>
    <template #company>Burke IT Consulting| Atlanta, GA | July 2019 to July 2021</template>
    <ul>
      <li>
        Developed a web application and dashboard for customers to view their security products and related security events.  
      </li>
      <li>
        Designed and developed a customer portal using Laravel, PHP, MySQL, Vue.js and Bootstrap.
      </li>
      <li>
        Designed an application and API for customers to check validity of their incoming calls using Twilio.
      </li>
    </ul>
  </JobItem>

  <JobItem>
    <template #icon>
      <CommandIcon />
    </template>
    <template #heading>Communications and Systems Specialist (Full Stack Developer)</template>
    <template #company>The Salvation Army Southern Territorial Headquarters | Atlanta, GA | July 2010 to June 2019</template>
    <ul>
      <li>Developed national disaster services website (sal.army) and underlying applications for volunteer training & availability.</li>
      <li>Centralized information-sharing, data management and reporting for Emergency Disaster Services through the development of online Incident Management Suite for real-time resource allocation and service statistics.</li>
      <li>Delivered nationwide cost-savings through development of centralized ID badge printing through online volunteer database and the use of PHP GD library. </li>
    </ul>
  </JobItem>
  <EducationSection>
    <template #icon>
      <EducationIcon/>
    </template>
    <template #heading>Education</template>
    <template #institution>Bachelor of Business Administration in Computer Information Systems (December 2024)</template>
    <template #location>Georgia State University | Atlanta, GA </template>
  </EducationSection>
</template>
