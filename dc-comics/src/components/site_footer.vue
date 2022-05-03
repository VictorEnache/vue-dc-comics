<template>
  <footer id="site_footer">
    <div class="container">
      <div class="dc_comics">
        <h3>DC COMICS</h3>
        <nav>
          <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
        </nav>
        <h3 class="shop">SHOP</h3>
        <nav>
            <ul>
                <li><a href="#">Videos</a></li>
                <li><a href="#">News</a></li>
            </ul>
        </nav>
      </div>
      <div class="dc">
        <h3>DC COMICS</h3>
        <nav>
          <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
        </nav>
      </div>
      <div class="sites">
        <h3>DC COMICS</h3>
        <nav>
          <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
        </nav>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "site_footer",
};
</script>

<style lang="scss">
#site_footer {
  ul {
    list-style: none;
  }

  .container {
    width: 1080px;
    margin: auto;
    background-color: gray;
    display: flex;
    column-gap: 2.5rem;
    padding: 3rem 0;
      
    .dc_comics{

        .shop{
            margin-top: 1rem;
        }
    }
    
  }
}
</style>
