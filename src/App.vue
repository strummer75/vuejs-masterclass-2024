<script setup lang="ts">
import { supabase } from '@/lib/supbaseClient'

console.log(supabase)
</script>

<template>
  <main>
    <router-view></router-view>
  </main>
</template>
