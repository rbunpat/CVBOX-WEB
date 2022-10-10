<script setup>
import Contact from './ContactItem.vue'
</script>

<template>
    <Contact>
        <template #contactus>
            ติดต่อเรา | Contact Us
        </template>
        <template #emailhead>
            อีเมล | Email
        </template>
        <template #email>
            <a href="mailto:contact@st-innovation.in.th">contact@st-innovation.in.th</a>
        </template>
    </Contact>
</template>