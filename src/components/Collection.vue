<template>
  <div class="container">
      <header id="header">
          <div class="sidebar">
              <b-button v-b-toggle.sidebar-1>Toggle Sidebar</b-button>
                <b-sidebar id="sidebar-1" title="Sidebar" shadow>
                <div class="px-3 py-2">
                    <p>
                    Cras mattis consectetur purus sit amet fermentum. Cras justo odio, dapibus ac facilisis
                    in, egestas eget quam. Morbi leo risus, porta ac consectetur ac, vestibulum at eros.
                    </p>
                    <b-img src="https://picsum.photos/500/500/?image=54" fluid thumbnail></b-img>
                </div>
                </b-sidebar>        
          </div>
          <div class="avt">

          </div>
      </header>
  </div>
</template>

<script>
export default {
    name: 'CollectionWrap'
}
</script>

<style>
    html, body, div, span, applet, object, iframe,h1, h2, h3, h4, h5, h6, p{
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    }

    ol, ul {
    list-style: none;
    }
    
    .container {        
    background-color: rgb(32, 30, 32);
    height: 100vh;
    align-items: center;
    display: flex;
    flex-direction: column;
    justify-content: center;

    }

</style>