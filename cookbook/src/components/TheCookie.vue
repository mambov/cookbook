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
    <template #heading>Pillsbury Devil's Food Cake Mix</template>

    <p>1 box</p>
  </RecipeItem>

  <RecipeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Pillsbury Vanilla Frosting</template>

    <p>?</p>
  </RecipeItem>

  <RecipeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Chocolate Chips</template>

    <p>?</p>
  </RecipeItem>

  <RecipeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Freeze Dried Strawberries</template>

    <p>2 bags (1 bag = 06oz = 17g)</p>
  </RecipeItem>

  <RecipeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Apple Sauce</template>

    <p>1/4 cup or 2 eggs</p>
  </RecipeItem>

  <RecipeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Vegetable Oil</template>

    <p>1/2 cup</p>
  </RecipeItem>

  <br/>
  <div>
    References:
    <ul>
      <li><a href="https://www.youtube.com/shorts/9mbdmXafmL0">
        Strawberry Cookies Part 1
      </a></li>
      <li><a href="https://www.youtube.com/shorts/fMIulC260bk">
        Strawberry Cookies Part 2
      </a></li>
      <li><a href="https://www.youtube.com/shorts/pD-J_9h6-FI">
        Applesauce as a replacement for eggs?
      </a></li>
    </ul>
  </div>

  
</template>
