
<template>
  <div>
    <div class="panel panel-default">
      <div class="panel-body">
        <div class="form-vertical">
          <div class="row">
            <div class="col-md-2 form-group">
              <label>出发地</label>
              <el-select v-model="value" placeholder="请选择">
                <el-option
                  v-for="item in startOpt"
                  :key="item.value"
                  :label="item.label"
                  :value="item.value">
                </el-option>
              </el-select>
            </div>
            <div class="col-md-2 form-group">
              <label>目的地</label>
              <el-select v-model="value" placeholder="请选择">
                <el-option
                    v-for="item in startOpt"
                    :key="item.value"
                    :label="item.label"
                    :value="item.value">
                  </el-option> 
              </el-select>
            </div>
            <div class="col-md-2 form-group">
              <label>途径地点</label>
              <el-select v-model="value" placeholder="请选择">
                <el-option
                    v-for="item in startOpt"
                    :key="item.value"
                    :label="item.label"
                    :value="item.value">
                </el-option>
              </el-select>
              
            </div>
            <div class="col-md-2 form-group">
              <label>乘车日期</label>
              <el-select v-model="value" placeholder="请选择">
                <el-option
                    v-for="item in startOpt"
                    :key="item.value"
                    :label="item.label"
                    :value="item.value">
                </el-option>
              </el-select>  
            </div>
            <div class="col-md-2 form-group">
              <label>目的地</label>
              <el-select v-model="value" placeholder="请选择">
                <el-option
                    v-for="item in startOpt"
                    :key="item.value"
                    :label="item.label"
                    :value="item.value">
                </el-option>
              </el-select>
            </div>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>

export default {
  name: 'Home',
  data () {
    return {
      startOpt: [
        {
          value: 1,
          label: '北京'
        }, {
          value: 2,
          label: '保定'
        }
      ],
      value: ''
    }
  },
  components: {
  }

}
</script>


<style scoped>

</style>
