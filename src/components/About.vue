<script setup lang="ts">
import { name, careerSummary, resumeLink, nameIcon  } from '../data/data'
</script>

<template>
  <section id="about" class="about">
    <div class="about-box">
    <img :src="nameIcon" alt="icon" class="name-icon" />
      <h2 class="name-heading">
        
        {{ name }}
      </h2>
      <p class="summary">{{ careerSummary }}</p>
      <a :href="resumeLink" target="_blank" class="resume-link">View Resume</a>
    </div>
  </section>
</template>
