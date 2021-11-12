<template>
  <main id="site_main">
    <div id="content_section">
      <div class="container">
        <h1>Content goes here</h1>
      </div>
    </div>
    <!-- /#content_section -->
    <div id="card_section">
      <div class="container">
        <div class="row">
          <div class="col-5">
            <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
            <p>digital comics</p>
          </div>
          <div class="col-5">
            <img src="../assets/img/buy-comics-merchandise.png" alt="" />
            <p>dc merchandise</p>
          </div>
          <div class="col-5">
            <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
            <p>subscriptions</p>
          </div>
          <div class="col-5">
            <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
            <p>comic shop locator</p>
          </div>
          <div class="col-5">
            <img
              src="../assets/img/buy-dc-power-visa.svg"
              alt=""
              class="small"
            />
            <p>dc power visa</p>
          </div>
        </div>
      </div>
    </div>
    <!-- /#card_section -->
    <div id="footer_section">
      <div class="container">
        <div class="footer_section_menu">
          <div class="row">
            <div class="col-5 double_list">
              <div class="list">
                <h2>Dc Comics</h2>
                <ul>
                  <li><a href="">Characters</a></li>
                  <li><a href="">Comics</a></li>
                  <li><a href="">Movie</a></li>
                  <li><a href="">TV</a></li>
                  <li><a href="">Games</a></li>
                  <li><a href="">Videos</a></li>
                  <li><a href="">News</a></li>
                </ul>
              </div>
              <div class="list">
                <h2>Shop</h2>
                <ul>
                  <li><a href="">Shop DC</a></li>
                  <li><a href="">Shop DC Collectibles</a></li>
                </ul>
              </div>
            </div>
            <div class="col-5">
              <div class="list">
                <h2>DC</h2>
                <ul>
                  <li><a href="">Terms Of Use</a></li>
                  <li><a href="">Privacy policy (New)</a></li>
                  <li><a href="">Ad Choices</a></li>
                  <li><a href="">Advertisting</a></li>
                  <li><a href="">Jobs</a></li>
                  <li><a href="">Subscriptions</a></li>
                  <li><a href="">Talent Workshop</a></li>
                  <li><a href="">CPSC Certificates</a></li>
                  <li><a href="">Ratings</a></li>
                  <li><a href="">Shop Help</a></li>
                  <li><a href="">Contact Us</a></li>
                </ul>
              </div>
            </div>
            <div class="col-5">
              <div class="list">
                <h2>SITES</h2>
                <ul>
                  <li><a href="">DC</a></li>
                  <li><a href="">MAD Magazine</a></li>
                  <li><a href="">DC Kids</a></li>
                  <li><a href="">DC Universe</a></li>
                  <li><a href="">DC Power Visa</a></li>
                </ul>
              </div>
            </div>
            <div class="col-5"></div>
            <div class="col-5"></div>
          </div>
        </div>
        <div class="footer_section_logo"></div>
      </div>
    </div>
    <!-- /#footer_section -->
  </main>
</template>
<script>
export default {
  data() {
    return {
      superheros: [
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
          price: "$19.99",
          series: "Action Comics",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
          price: "$3.99",
          series: "American Vampire 1976",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
          price: "$16.99",
          series: "Aquaman",
          type: "graphic novel",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
          price: "$2.99",
          series: "Batgirl",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$3.99",
          series: "Batman",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$2.99",
          series: "Batman Beyond",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
          price: "$3.99",
          series: "Batman/Superman",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
          price: "$4.99",
          series: "Batman/Superman Annual",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
          price: "$5.99",
          series: "Batman: The Joker War Zone",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
          price: "$6.99",
          series: "Batman: Three Jokers",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
          price: "$4.99",
          series: "Batman: White Knight Presents: Harley Quinn",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
          price: "$16.99",
          series: "Catwoman",
          type: "graphic novel",
        },
      ],
    };
  },
};
</script>
<style scoped lang="scss">
#site_main {
  height: 655px;
  color: #ffffff;
  #content_section {
    height: 135px;
    width: 100%;
    background-color: #1c1c1c;
    .container {
      display: flex;
      align-items: center;
      h1 {
        margin-left: 20px;
      }
    }
  }
  #card_section {
    height: 155px;
    width: 100%;
    background-color: #0282f9;
    .row {
      display: flex;
      height: 100%;
      .col-5 {
        width: calc(100% / 5);
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        img {
          height: 50px;
          margin-right: 10px;
          &.small {
            height: 35px;
          }
        }
        p {
          text-transform: uppercase;
        }
      }
    }
  }
  #footer_section {
    height: 367px;
    width: 100%;
    background-image: url("../assets/img/footer-bg.jpg");
    .container {
      height: 100%;
      display: flex;
      .footer_section_menu {
        height: 100%;
        width: calc(100% / 2);
        .row {
          height: 100%;
          display: flex;
          .col-5 {
            width: calc(100% / 5);
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            &.double_list {
              flex-direction: column;
              justify-content: flex-start;
            }
            ul {
              list-style: none;
              a {
                text-decoration: none;
                color: white;
              }
            }
            .list {
              width: 100%;
              text-align: start;
              margin: 20px 0;
              h2 {
                margin-bottom: 15px;
              }
            }
          }
        }
      }
      .footer_section_logo {
        height: 100%;
        width: calc(100% / 2);
        background-image: url("../assets/img/dc-logo-bg.png");
        background-position: center;
        background-repeat: no-repeat;
      }
    }
  }
}
/* #0282F9; */
</style>

