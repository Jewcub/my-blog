<template>
  <section>
    <b-container id="blog-header" class="p-0 m-0">
      <g-image id="writing" src="~/resources/images/writing.png"></g-image>

      <b-row class="blog-header-row p-0 m-0">
        <b-col cols="12" class="p-0 m-0">
          <p id="blog-title" class="title lg-txt">Blog</p>
        </b-col>
      </b-row>
      <b-row class="blog-header-row">
        <b-col cols="12" class="p-0 m-0 d-flex justify-content-end">
          <p id="blog-header-subtitle" class="title sm-txt mr-1">
            ed | tech | & more
          </p>
        </b-col></b-row
      >
    </b-container>
  </section>
</template>

<script>
export default {
  props: ['totalCount'],
};
</script>
<style>
#blog-header {
  background-color: #339cd0;
  justify-content: stretch;
  width: 100%;
  height: 170px;
  max-width: none;
}
#writing {
  position: absolute;
  top: 0;
  left: 0;
  mix-blend-mode: darken;
  margin-right: auto;
  opacity: 0.1;
}
.blog-header-row {
  width: 100%;
  height: 50%;
}
#blog-title {
  text-align: center;
  margin-top: 40px;
  padding: 0;
}
#blog-header-subtitle {
  text-align: right;
  align-self: flex-end;
  margin-bottom: 0;
  padding: 0;
}
</style>
