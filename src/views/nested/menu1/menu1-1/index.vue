<template >
  <div style="padding:30px;">
    <el-alert :closable="false" title="menu 1-1" type="success">
      <el-input type="text"/>
      <router-view />
    </el-alert>
  </div>
</template>
<script>
export default {
  name: 'Menu1'
}
</script>
