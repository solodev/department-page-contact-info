# department-page-contact-info
Department pages are mini-homepages in and of themselves for many organizations. For end-users, they want the ability to see a glance of what a department does as well as all relevant contact information. You can specify a department overview, featured biography, and all pertinent contact information in one easily digestible layout.

## Tutorial
For detailed instruction's, view Solodev's [How to Add Relevant Contact Information to Your Department Pages](http://www.solodev.com/blog/web-design/how-to-add-relevant-contact-information-to-your-department-pages.stml)

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/hsg3kmre/).

## HTML
The tutorial contains the following basic HTML markup.

```
<section class="section section--content-department section--content-detail py-5">
  <div class="container">
    <div class="row">
      <div class="col-xl-9 col-lg-8 section--content-detail__item">
        <h1>Lunar Mining</h1>
        <div class="breadcrumb mb-3 mb-lg-5 pb-2">
          <a class="fileTrail" href="/">Home</a> <span class="fileTrailDividers">
            <i class="fa fas angle-right"></i></span>
          <a class="fileTrail" href="/departments/">Departments</a>
          <span class="fileTrailDividers"><i class="fa fas angle-right"></i></span>
          <span class="fileTrailCurrent">Lunar Mining</span>
        </div>
        <article>

          <p>Hydrogen atoms dispassionate extraterrestrial observer encyclopaedia galactica radio telescope network of wormholes light years. Preserve and cherish that pale blue dot extraordinary claims require extraordinary evidence not a sunrise but a galaxyrise cosmic ocean cosmic ocean venture. Brain is the seed of intelligence emerged into consciousness dream of the mind's eye the carbon in our apple pies something incredible is waiting to be known rich in heavy atoms and billions upon billions upon billions upon billions upon billions upon billions upon billions.</p>

          <hr class="mb-0">

          <div class="section--content-department__person clearfix">
            <div class="row">
              <div class="col-md-3 text-center text-md-left">
                <img alt="County Administrator - Adam Paul" class="img-fluid mb-3 mb-sm-0" src="https://raw.githubusercontent.com/solodev/department-page-contact-info/master/images/Team_Commander.jpg">
              </div>
              <div class="col-md-9">
                <h2 class="mt-0 text-center text-md-left">Adam Paul</h2>
                <span class="text-center text-md-left">Mining Operations</span>
                <p>Adam has been a commander for LunarXP since 2010. Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. </p>
              </div>
            </div>
          </div>
        </article>
      </div>
      <div class="col-xl-3 col-lg-4">

        <aside>
          <div class="box-date d-flex">
            <i class="fa fas fa-user"></i>
            <p><strong>Adam Paul</strong><br>Mining Operations</p>
          </div>

          <div class="box-date d-flex">
            <i class="fa fas fa-envelope"></i>
            <a href="mailto:operations@lunarxp.com">Email Department</a>
          </div>

          <div class="box-date d-flex">
            <i class="fa fas fa-mobile-alt"></i>
            <a href="tel:941.743.1944">800.123.4567</a>
          </div>

          <div class="box-date d-flex">
            <i class="fa fas fa-map-marker-alt"></i>
            <a href="https://goo.gl/maps/SLg7hXzDKGvPpD4t9" target="_blank">Kennedy Space Center<br>Port Charlotte, FL 32899</a>
          </div>

          <div class="box-date d-flex">
            <i class="far fa-clock"></i>
            <div class="office-hours">
              <p>Monday-Wednesday<br>
                8:00 am - 4:30 pm</p>
              <p>Thursday<br>
                9:00 am - 12:30 pm</p>
              <p>Friday<br>
                Closed</p>
            </div>
          </div>

          <div class="box-date d-flex">
            <i class="fa fab fa-facebook-f"></i> <a href="https://facebook.com" target="_blank">Facebook</a>
          </div>

          <div class="box-date d-flex">
            <i class="fa fab fa-twitter"></i> <a href="https://twitter.com/" target="_blank">Twitter</a>
          </div>

          <div class="box-date d-flex">
            <i class="fa fab fa-instagram"></i> <a href="https://instragram.com" target="_blank">Instagram</a>
          </div>

          <div class="box-date d-flex">
            <i class="fa fab fa-youtube"></i> <a href="https://youtube.com" target="_blank">YouTube</a>
          </div>

        </aside>
      </div>
    </div>
  </div>
</section>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<!-- FontAwesome CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.css">
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
```