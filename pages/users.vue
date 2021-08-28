<template>
  <div>
    <ul>
      <li><nuxt-link active-class="active" exac-active-class="exact-active" to="/users">Users Page</nuxt-link></li>
      <li><nuxt-link active-class="active" exac-active-class="exact-active" to="/users/20">Users Detail</nuxt-link></li>
      <li><nuxt-link active-class="active" exac-active-class="exact-active" to="/users/setting">Users Setting</nuxt-link></li>
    </ul>
    <h1>User Page</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad, doloremque harum. Illo minima alias voluptas accusamus ipsam. Vel nesciunt molestias, sunt porro molestiae neque animi dolore sapiente culpa itaque quibusdam!</p>
    <nuxt-child />
  </div>
</template>

<script>
export default {

}
</script>
