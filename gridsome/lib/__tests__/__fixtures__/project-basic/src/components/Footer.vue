<template>
  <div class="footer">
    <span class="meta-data-1">{{ $static.metadata.myTest.value }}</span>
    <span class="meta-data-2">{{ $static.metadata.pluginValue }}</span>
  </div>
</template>

<static-query>
query Footer {
  metadata {
    myTest {
      value
    }
    pluginValue
  }
}
</static-query>
