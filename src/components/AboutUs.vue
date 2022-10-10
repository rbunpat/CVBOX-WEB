<script setup>
import AboutUs from './AboutItem.vue'
</script>


<template>

<AboutUs>
    <template #head1>
        เกี่ยวกับเรา | About Us
    </template>
    <template #thaidetail>
        พวกเราเป็นนักเรียนจากโรงเรียนสุราษฎร์ธานี เราคิดค้นสิ่งประดิษฐ์นี้ขึ้นมาเพื่อใช้ในการคัดกรองผู้ที่ป่วยและมีความเสี่ยงต่อการติดเชื้อโควิด-19 โดยใช้การวัดอุณหภูมิและการตรวจจับการใส่แมสก์ โดยทำให้เป็น Open-Source คือเปิด Source Code ให้ทุกคนใช้งานได้ฟรี โดยไม่มีค่าใช้จ่ายใดๆ
    </template>
    <template #engdetail>
        We are students from Suratthani School. The goal of this project is to make an affordable and open-source solution for screening COVID-19 patients and people at risk of infection. The solution uses temperature measurement and face mask detection. The project is open-source, meaning that the source code is free for everyone to use without any cost.
    </template>
    <template #teammemsheading>
        สมาชิก | Members
    </template>
    <template #members>
        <ul>
            <li>นายพศิน นุ้ยเจริญ Phasin Nuycharoen</li>
            <li>นายภูรินท์ พวงใส Phurin Puangsai</li>
            <li>นายรชาทัช บุญพัฒน์ Rachatat Bunpat</li>
        </ul>
    </template>
</AboutUs>

</template>
