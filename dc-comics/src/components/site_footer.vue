<template>
  <footer id="site_footer">
    <div class="container">
      <div class="row">
        <div class="col" :key="colonna" v-for="colonna in colonne">
          <h3>{{ colonna.title }}</h3>
          <nav>
            <ul>
              <li :key="link" v-for="link in colonna.links">
                <a href="#">{{ link }}</a>
              </li>
            </ul>
          </nav>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "site_footer",

  data() {
    return {
      colonne: [
        {
          title: "DC COMICS",
          links: [
            "Characters",
            "Comics",
            "Movies",
            "TV",
            "Games",
            "Videos",
            "News",
          ],
        },

        {
          title: "SHOP",
          links: ["Shop DC", "Shop DC Collectibles"],
        },

        {
          title: "DC",
          links: [
            "Terms OF Use",
            "Privacy policy (New)",
            "Ad Choices",
            "Advertising",
            "Jobs",
            "Subscriptions",
            "Talent Workshop",
            "CPSC Certificates",
            "Ratings",
            "Shop Help",
            "Contact Us",
          ],
        },

        {
          title: "SITES",
          links: [
            "DC",
            "MAD Magazzine",
            "DC Kids",
            "DC universe",
            "DC Power Visa",
          ],
        },
      ],
    };
  },
};
</script>

<style lang="scss">
#site_footer {
  background-image: url("../assets/img/footer-bg.jpg");

  ul {
    list-style: none;
  }

  .container {
    background-image: url('../assets/img/dc-logo-bg.png');
    background-repeat: no-repeat;
    background-position: right;
    
    padding: 50px 0;
    
    width: 1080px;
    margin: auto;
    display: flex;

    .row {
      max-height: 400px;
      width: 50%;
      display: flex;
      flex-direction: column;
      flex-wrap: wrap;
      align-content: flex-start;

      .col {
        width: calc(100% * 3 / 12);
        margin-top: 1rem;

        h3 {
          color: white;
        }

        nav {
          ul {
            li {
              a {
                color: gray;
                font-size: 12px;
                text-decoration: none;
              }
            }
          }
        }
      }
    }
  }
}
</style>
