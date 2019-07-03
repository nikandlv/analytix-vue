<template>
  <div>
    <header-section />
    <companies-section />
    <stat-section />
    <br/><br/><br/><br/>
  </div>
</template>
<script>
import HeaderSection from '../layouts/HeaderSection'
import CompaniesSection from '../layouts/CompaniesSection'
import StatSection from '../layouts/StatSection'
export default {
  components:{
    HeaderSection,
    CompaniesSection,
    StatSection
  }
}
</script>
