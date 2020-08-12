<template>
  <panel>
    <div slot="title">SwSketchBook 온라인 저지 가이드</div>
    <div class="content markdown-body">
      <ul>
        <li>01. 로그인 가이드
          <p>관리자 계정 로그인 방법 [아이디 : root, 비밀번호 : rootroot]<br>
          (관리자 계정 - 관련 공부한 문제 제출, 삭제 가능)<br><br>

          게스트 계정 로그인 방법 [아이디 : guest, 비밀번호 : guest]<br>
          (게스트 계정 - 문제 제출 가능)
          </p>
        </li>
      </ul>
    </div>
  </panel>
</template>

<script>
  export default {
    name: 'home'
  }
</script>

<style lang="less" scoped>
  .content {
    font-size: 16px;
    margin: 0 50px 40px 50px;
    > ul {
      list-style: disc;
      li {
        font-size: 16px;
        margin-top: 20px;
        &:first-child {
          margin-top: 0;
        }
        p {
          font-size: 14px;
          margin-top: 5px;
        }
      }
    }
  }
</style>
