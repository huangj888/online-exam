<template>
  <div class="footer">
    <div class="links">
      <a href="#">代码仓</a>
      <a href="#">关于我</a>
      <a href="#">联系我</a>
    </div>
    <div class="copyright">Copyright &copy; 2023 guang dong bai yun</div>
  </div>
</template>

<script>
export default {
  name: 'GlobalFooter',
  data() {
    return {}
  },
}
</script>

<style lang="less" scoped>
.footer {
  padding: 0 16px;
  margin: 24px 0 24px;
  text-align: center;

  .links {
    margin-bottom: 8px;

    a {
      color: rgba(0, 0, 0, 0.45);

      &:hover {
        color: rgba(0, 0, 0, 0.65);
      }

      &:not(:last-child) {
        margin-right: 40px;
      }
    }
  }
  .copyright {
    color: rgba(0, 0, 0, 0.45);
    font-size: 14px;
  }
}
</style>
