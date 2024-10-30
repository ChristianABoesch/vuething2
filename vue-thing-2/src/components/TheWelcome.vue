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
    <template #heading>Factoid #1</template>

    Did you know that the average person only blinks once a day? Blink more and you become superior. This is absolutely true.
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Factoid #2</template>

    There is no human being alive today that could jump higher than the average house, neither are there any human beings recorded in history that were capable of doing so.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Factoid #3</template>

    A group of ferrets is called a gawk-and-run. This is because they all like to gawk at you and run away as a party. I know this from experience.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Factoid #4</template>

    The sun has never seen a shadow. This is mostly due to the fact that the sun has never seen anything.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Factoid #5</template>

    If you pour salt all around where you're standing, you create a personalized fortress of solitude. The only major effect it has is that you feel a little better about yourself, even though nothing in particular is different other than now you have a ring of salt on the floor.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Factoid #6</template>

    For the average person to discover true fulfilment and happiness, all they'd need to do is
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">become a sponsor</a> of our little thing. Not much else really.
  </WelcomeItem>
</template>
