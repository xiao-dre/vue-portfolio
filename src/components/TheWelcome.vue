<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Education</template>

    I have a high school education in SMA Santo Kristofus 2 and currently im learning in Bina Nusantara University.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Organization</template>
    I've joined an organization called HIMTI Binus (Himpunan Teknik Informatika Bina Nusantara) as an web developer division and have an experience in HISHOT 2021 event as a member of the design and documentation division
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Working Experience</template>
    I've been working as an laboratory in assistant in Bina Nusantara University. As an laboratory assistant, my job is to teach students, create cases, and check the students answers. Other than that, I also have working experience as a front-end developer in Skinfix.id
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Tools</template>
    I've learned programming using tools such as VueJS, ReactJS, Laravel, and more using some programming languages. I also learned database engines using MySQL and MSSQL.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>LinkedIn Profile</template>
    Check out my 
    <a target="_blank" href="https://www.linkedin.com/in/andreas-alexander-045a521a9/">LinkedIn Profile</a>.
  </WelcomeItem>
</template>
