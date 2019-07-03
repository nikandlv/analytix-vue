<template>
  <div>
    <header-section />
    <companies-section />
    <stat-section />
    <why-section />
    <steps-section />
    <quotes-section />
    <footer-section />
  </div>
</template>
<script>
import HeaderSection from '../layouts/HeaderSection'
import CompaniesSection from '../layouts/CompaniesSection'
import StatSection from '../layouts/StatSection'
import WhySection from '../layouts/WhySection'
import StepsSection from '../layouts/StepsSection'
import QuotesSection from '../layouts/QuotesSection'
import FooterSection from '../layouts/FooterSection'
export default {
  components:{
    HeaderSection,
    CompaniesSection,
    StatSection,
    WhySection,
    StepsSection,
    QuotesSection,
    FooterSection
  }
}
</script>
