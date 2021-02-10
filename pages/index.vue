<template>
  <div class="site-wrapper">
    <TheHeader>
    </TheHeader>
    <main class="main" role="main">
      <TopSection>
      </TopSection>
      <TurnOn>
      </TurnOn>
    </main>

  </div>
</template>

<script>

import TheHeader from "~/components/TheHeader";
import TopSection from "~/components/TopSection";
import TurnOn from "~/components/TurnOn";

export default {
  components: {
    TurnOn,
    TopSection,
    TheHeader

  }
}
</script>
<style lang="scss">

</style>

