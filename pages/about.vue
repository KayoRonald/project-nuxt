<template>
   <div class="container">
    <CAccordion allowMultiple>
      <CAccordionItem>
        <CAccordionHeader>
          <CBox flex="1" textAlign="left">
            Section 1 title
          </CBox>
          <CAccordionIcon />
        </CAccordionHeader>
        <CAccordionPanel pb="4">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
          tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
          veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
          commodo consequat.
        </CAccordionPanel>
      </CAccordionItem>
      <CAccordionItem>
        <CAccordionHeader>
          <CBox flex="1" textAlign="left">
            Section 2 title
          </CBox>
          <CAccordionIcon />
        </CAccordionHeader>
        <CAccordionPanel pb="4">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
          tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
          veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
          commodo consequat.
        </CAccordionPanel>
      </CAccordionItem>
    </CAccordion>
  </div>
</template>

<script lang="js">
import {
  CAccordion,
  CAccordionItem,
  CAccordionHeader,
  CBox,
  CAccordionIcon,
  CAccordionPanel
} from '@chakra-ui/vue'
// import from 'react-icons/fi'
export default {
  name: 'App',
  components: {
    CAccordion,
    CAccordionItem,
    CAccordionHeader,
    CBox,
    CAccordionIcon,
    CAccordionPanel
  }
}
</script>
