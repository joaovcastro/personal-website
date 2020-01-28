<template>
    <div class="card">
      <div class="logo">
        <a href="https://www.edreamsodigeo.com/" target="_blank">
          <img src="../assets/edo.png" width="50">
        </a>
      </div>
       <div class="info">
        <h1>eDreams ODIGEO</h1>
        <h3> Frontend Software Engineer </h3>
        <h4> Aug 2018 - Present </h4>
      </div>
      <div class="technologies">
        <ul>
          <li> Backbone.js </li>
          <li> Java </li>
          <li> JavaServer Pages</li>
          <li> HTML</li>
        </ul>
      </div>
      <div class="technologies">
        <ul>
          <li> SCSS</li>
          <li> jQuery</li>
          <li> Jenkins</li>
        </ul>
      </div>
      </div>
</template>

<script>
export default {
  name: 'Card',
  props: {
    msg: String,
  },
};
</script>

<style scoped lang="scss">
  .card {
    width: 500px;
    margin-bottom: 50px;
    margin-left: 25%;
    text-align: left;
    display: flex;

    .logo img {
      margin-top: 15px;
      margin-right: 50px;
    }

    .info {
      display: block;
      padding-right: 30px;
      border-right: 1px solid grey;
    }

    .technologies {
      ul {
        li {
          margin-bottom: 6px;
          font-size: 11px;
        }
      }
    }

  }


  h1 {
    font-size: 14px;
  }

  h3 {
    font-size: 12px;
    font-weight: 500;
  }

  h4 {
    font-size: 10px;
    color: gray;
    font-weight: 500;
  }


</style>
