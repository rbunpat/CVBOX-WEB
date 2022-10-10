<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import DiscordIcon from './icons/DiscordIcon.vue'
</script>

<template>
    <WelcomeItem>
        <template #icon>
            <DocumentationIcon />
        </template>
        <template #heading>
        วิดิโอแนะนำโครงงาน | Project Presentation Video
        </template>
        <h3>วิดิโอนี้เป็นวิดิโออธิบายเกี่ยวกับจุดประสงค์ คุณสมบัติ และหลักการทำงานต่างๆของโครงงานนี้</h3>
        <h3>This is the presentation video for this project. It contains the project's background, explanations and demonstrations.</h3>
        <a href="https://youtube.com/watch?v=bqV3iKPv4OA" target="_blank" rel="noopener">Video Link (YouTube)</a>
    </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>โค้ด Open-Source | Open-Source Code</template>
    <h3>โครงงานนี้เป็นโครงงานที่โอเพนซอร์ส สามารถดู Source Code ได้บน Github โครงงานนี้ใช้ใบอนุญาตประเภท GPL v2.0 และ MIT</h3>
    <h3>This project is entirely open source. Yes, this website is also open source. You can find the source code and schematics on Github. The code is licensed with GPL v2.0 and MIT.</h3>
    <a href="https://github.com/rbunpat/CVBOX-INDEX" target="_blank" rel="noopener">Source Code on Github</a>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DiscordIcon />
    </template>
    <template #heading>ตัวอย่างเซิร์ฟเวอร์ Discord | Demo Discord Server</template>
    <h3>เข้าร่วมเซิร์ฟเวอร์ดิสคอร์ดเพื่อดูการใช้งานของบอทแจ้งเตือนทางดิสคอร์ด</h3>
    <h3>Join this Discord server to see the Discord bot in action.</h3>
    <a href="https://discord.gg/NwmxJf89wp" target="_blank" rel="noopener">Invite Link</a>
    
  </WelcomeItem>

</template>

<!-- This is the presentation video for this project. It contains the project's background, explanations and demonstrations.
วิดิโอนี้เป็นวิดิโออธิบายเกี่ยวกับจุดประสงค์ คุณสมบัติ และหลักการทำงานต่างๆของโครงงานนี้
This project is entirely open source. Yes, this website is also open source. You can find the source code and schematics on Github. The code is licensed with GPL v2.0 and MIT.
โครงงานนี้เป็นโครงงานที่โอเพนซอร์ส สามารถดู Source Code ได้บน Github โครงงานนี้ใช้ใบอนุญาตประเภท GPL v2.0 และ MIT
Join this Discord server to see the Discord bot in action.
เข้าร่วมเซิร์ฟเวอร์ดิสคอร์ดเพื่อดูการใช้งานของบอทแจ้งเตือนทางดิสคอร์ด -->

