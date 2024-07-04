<script setup lang="ts">
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
import RecipeItem from './RecipeItem.vue'
</script>

<template>
  <RecipeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Apple Sauce</template>

    <p>1/4 cup</p>
  </RecipeItem>
</template>
