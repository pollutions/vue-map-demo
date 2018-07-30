<template>
  <div>
  <el-container style="height: 500px; border: 0px solid #eee">
  <el-container>
    <el-header>
       <span class="big">广西地理信息展示系统</span>
       <div class="icon-right">
        <el-button-group>
          <el-button type="info" size="mini" class="button">
            <img :src="search" class="icon-font">
            <t1 class="icon-text">搜索</t1>
          </el-button>
        
          <el-button type="info" size="mini" class="button">
            <img :src="ranging" class="icon-font">
            <t1 class="icon-text">测距</t1>
          </el-button>

          <el-button type="info" size="mini" class="button">
            <img :src="measurement" class="icon-font">
            <t1 class="icon-text">测面</t1>
          </el-button>
        
          <el-button type="info" size="mini" class="button">
            <img :src="clear" class="icon-font">
            <t1 class="icon-text">清除</t1>
          </el-button>
        
          <el-button type="info" size="mini" class="button">
            <img :src="punctuation" class="icon-font">
            <t1 class="icon-text">标点</t1>
          </el-button>
        
          <el-button type="info" size="mini" class="button">
            <img :src="line" class="icon-font">
            <t1 class="icon-text">标线</t1>
          </el-button>

          <el-button type="info" size="mini" class="button">
            <img :src="area" class="icon-font">
            <t1 class="icon-text">标线</t1>
          </el-button>
        
          <el-button type="info" size="mini" class="button">
            <img :src="layer" class="icon-font">
            <t1 class="icon-text">标面</t1>
          </el-button>
        
        </el-button-group>
       </div>
    </el-header>
    <el-main>
      666
    </el-main>
  </el-container>
</el-container>
</div>
</template>

<script>
 export default {
    data() {
      return {
        layer:require('common/image/layer.png'),
        area:require('common/image/area.png'),
        line:require('common/image/line.png'),
        punctuation:require('common/image/punctuation.png'),
        clear:require('common/image/clear.png'),
        measurement:require('common/image/measurement-area.png'),
        ranging:require('common/image/ranging.png'),
        search: require('common/image/search.png')
      };
    }
 };
</script>
