<template>
  <div>
    <el-form>
      <el-form-item label="名字">
        <el-input v-model.trim="user.name" />
      </el-form-item>
      <el-form-item label="性别">
        <el-input v-model.trim="user.sex" />
      </el-form-item>
      <el-form-item label="学院">
        <el-input v-model.trim="user.college" />
      </el-form-item>
      <el-form-item label="工号">
        <el-input v-model.trim="user.realid" />
      </el-form-item>
    </el-form>
  </div>
</template>

<script>
export default {
  props: {
    user: {
      type: Object,
      default: () => {
        return {
        };
      },
    },
  },
  methods: {
  },
};
</script>
