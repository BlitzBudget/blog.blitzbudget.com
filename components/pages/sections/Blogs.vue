<template>
  <div class="cd-section" id="blogs">
    <!--     *********     BLOGS 1      *********      -->
    <div class="blogs-1" id="blogs-1">
      <div class="container">
        <div class="row">
          <div class="col-md-10 ml-auto mr-auto">
            <h2 class="title">Latest Blogposts</h2>
            <br />
            <card type="blog" plain>
              <div class="row" slot="image">
                <div class="col-md-5">
                  <img class="img img-raised rounded" src="img/examples/card-blog4.jpg" />
                </div>
                <div class="col-md-7">
                  <h6 class="category text-info">Enterprise</h6>
                  <h3 class="card-title">
                    <nuxt-link to="#pablo">Warner Music Group buys concert discovery service
                      Songkick</nuxt-link>
                  </h3>
                  <p class="card-description">
                    Warner Music Group announced today it’s acquiring the
                    selected assets of the music platform Songkick, including
                    its app for finding concerts and the company’s trademark.
                    Songkick has been involved in a lawsuit against the major…
                    <nuxt-link to="#pablo"> Read More </nuxt-link>
                  </p>
                  <p class="author">
                    by
                    <nuxt-link to="#pablo">
                      <strong>Sarah Perez</strong>
                    </nuxt-link>, 2 days ago
                  </p>
                </div>
              </div>
            </card>
            <card type="blog" plain>
              <div class="row">
                <div class="col-md-7">
                  <h6 class="category text-danger">
                    <em class="now-ui-icons now-ui-icons media-2_sound-wave"></em>
                    Startup
                  </h6>
                  <h3 class="card-title">
                    <nuxt-link to="#pablo">Insticator raises $5.2M to help publishers</nuxt-link>
                  </h3>
                  <p class="card-description">
                    Insticator is announcing that it has raised $5.2 million in
                    Series A funding. The startup allows online publishers to
                    add quizzes, polls and other interactive elements (either
                    created by Insticator or by the publisher themselves) to
                    their stories.
                    <nuxt-link to="#pablo"> Read More </nuxt-link>
                  </p>
                  <p class="author">
                    by
                    <nuxt-link to="#pablo">
                      <strong>Anthony Ha</strong>
                    </nuxt-link>, 5 days ago
                  </p>
                </div>
                <div class="col-md-5">
                  <div class="card-image">
                    <img class="img img-raised rounded" src="img/examples/card-blog6.jpg" />
                  </div>
                </div>
              </div>
            </card>
          </div>
        </div>
      </div>
    </div>
    <!--     *********    END BLOGS 1      *********      -->
    <!--     *********     BLOGS 2      *********      -->
    <div class="blogs-2" id="blogs-2">
      <div class="container">
        <div class="row">
          <div class="col-md-10 ml-auto mr-auto">
            <h2 class="title">Latest Blogposts 2</h2>
            <br />
            <div class="row justify-content-center">
              <div class="col-md-5">
                <card type="blog" plain>
                  <div class="card-image">
                    <nuxt-link to="#pablo">
                      <img class="img img-raised rounded" src="img/examples/card-blog7.jpg" />
                    </nuxt-link>
                  </div>
                  <div class="card-body">
                    <h6 class="category text-info">Enterprise</h6>
                    <h5 class="card-title">
                      <nuxt-link to="#pablo">Alexa brings hands-free TV to more devices</nuxt-link>
                    </h5>
                    <p class="card-description">
                      Alexa’s latest trick is offering a hands-free TV viewing
                      experience, that will allow consumers to turn on or off
                      their television, change inputs, fast forward, rewind and
                      more, without having to first invoke a specific skill, or
                      even press a button on their remote.
                      <nuxt-link to="#pablo">Read More </nuxt-link>
                    </p>
                  </div>
                </card>
              </div>
              <div class="col-md-5">
                <card type="blog" plain>
                  <div class="card-image">
                    <nuxt-link to="#pablo">
                      <img class="img img-raised rounded" src="img/examples/card-blog9.jpg" />
                    </nuxt-link>
                  </div>
                  <div class="card-body">
                    <h6 class="category text-success">M&A</h6>
                    <h5 class="card-title">
                      <nuxt-link to="#pablo">Uber, Yandex combine ridesharing and UberEATS in
                        $3.72B. JV</nuxt-link>
                    </h5>
                    <p class="card-description">
                      As Uber works through a huge amount of internal management
                      turmoil, the company is also consolidating and
                      rationalizing more of its international business. Today,
                      the company announced it will be combining its
                      rides-on-demand business and UberEATS.
                      <nuxt-link to="#pablo">Read More</nuxt-link>
                    </p>
                  </div>
                </card>
              </div>
            </div>
            <div class="row justify-content-center">
              <div class="col-md-5">
                <card type="blog" plain>
                  <div class="card-image">
                    <nuxt-link to="#pablo">
                      <img class="img img-raised rounded" src="img/examples/card-blog16.jpg" />
                    </nuxt-link>
                  </div>
                  <div class="card-body">
                    <h6 class="category text-info">Music</h6>
                    <h5 class="card-title">
                      <nuxt-link to="#pablo">The Affect Music Has On Different Teens</nuxt-link>
                    </h5>
                    <p class="card-description">
                      Music is something that every person has his or her own
                      specific opinion about. Different people have different
                      taste, and various types of music have many ways of
                      leaving an impact on someone.
                      <nuxt-link to="#pablo">Read More </nuxt-link>
                    </p>
                  </div>
                </card>
              </div>
              <div class="col-md-5">
                <card type="blog" plain>
                  <div class="card-image">
                    <nuxt-link to="#pablo">
                      <img class="img img-raised rounded" src="img/examples/card-blog15.jpg" />
                    </nuxt-link>
                  </div>
                  <div class="card-body">
                    <h6 class="category text-success">Broadcasting</h6>
                    <h5 class="card-title">
                      <nuxt-link to="#pablo">Radio networks to broadcast a common radio format</nuxt-link>
                    </h5>
                    <p class="card-description">
                      Radio broadcasting is a unidirectional wireless
                      transmission over radio waves intended to reach a wide
                      audience. Stations can be linked in radio networks to
                      broadcast a common radio format.
                      <nuxt-link to="#pablo"> Read More </nuxt-link>
                    </p>
                  </div>
                </card>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--     *********    END BLOGS 2      *********      -->
    <!--     *********     BLOGS 3      *********      -->
    <div class="blogs-3">
      <div class="container">
        <div class="row">
          <div class="col-md-10 ml-auto mr-auto">
            <h2 class="title">Latest Blogposts 3</h2>
            <br />
            <card type="blog" plain>
              <div class="row">
                <div class="col-md-4">
                  <div class="card-image">
                    <img class="img img-raised rounded" src="img/examples/card-blog10.jpg" />
                  </div>
                </div>
                <div class="col-md-8">
                  <h3 class="card-title">
                    <nuxt-link to="#pablo">Rover raised $65 million for pet sitting</nuxt-link>
                  </h3>
                  <p class="card-description">
                    Finding temporary housing for your dog should be as easy as
                    renting an Airbnb. That’s the idea behind Rover, which
                    raised $65 million to expand its pet sitting and dog-walking
                    businesses..
                    <nuxt-link to="#pablo"> Read More </nuxt-link>
                  </p>
                  <div class="author">
                    <img v-lazy="'img/olivia.jpg'" alt="..." class="avatar img-raised" />
                    <span>Katie Roof</span>
                  </div>
                </div>
              </div>
            </card>
            <card type="blog" plain>
              <div class="row">
                <div class="col-md-4">
                  <div class="card-image">
                    <nuxt-link to="#pablo">
                      <img class="img img-raised rounded" src="img/examples/card-blog11.jpg" />
                    </nuxt-link>
                  </div>
                </div>
                <div class="col-md-8">
                  <h3 class="card-title">
                    <nuxt-link to="#pablo">MateLabs mixes machine learning with IFTTT</nuxt-link>
                  </h3>
                  <p class="card-description">
                    If you’ve ever wanted to train a machine learning model and
                    integrate it with IFTTT, you now can with a new offering
                    from MateLabs. MateVerse, a platform where novices can spin
                    out machine...
                    <nuxt-link to="#pablo"> Read More </nuxt-link>
                  </p>
                  <div class="author">
                    <img v-lazy="'img/james.jpg'" alt="..." class="avatar img-raised" />
                    <span>John Mannes</span>
                  </div>
                </div>
              </div>
            </card>
            <card type="blog" plain>
              <div class="row">
                <div class="col-md-4">
                  <div class="card-image">
                    <nuxt-link to="#pablo">
                      <img class="img img-raised rounded" src="img/examples/card-blog12.jpg" />
                    </nuxt-link>
                  </div>
                </div>
                <div class="col-md-8">
                  <h3 class="card-title">
                    <nuxt-link to="#pablo">US venture investment ticks up in Q2 2017</nuxt-link>
                  </h3>
                  <p class="card-description">
                    Venture investment in U.S. startups rose sequentially in the
                    second quarter of 2017, boosted by large, late-stage
                    financings and a few outsized early-stage rounds in tech and
                    healthcare..
                    <nuxt-link to="#pablo"> Read More </nuxt-link>
                  </p>
                  <div class="author">
                    <img v-lazy="'img/michael.jpg'" alt="..." class="avatar img-raised" />
                    <span>Devin Coldewey</span>
                  </div>
                </div>
              </div>
            </card>
          </div>
        </div>
      </div>
    </div>
    <!--     *********    END BLOGS 4      *********      -->
    <div class="blogs-4" id="blogs-4">
      <div class="container">
        <div class="row">
          <div class="col-md-8 ml-auto mr-auto">
            <h2 class="title">Latest Blogposts 4</h2>
            <br />
            <card type="blog" plain>
              <div class="card-image">
                <nuxt-link to="#pablo">
                  <img class="img img-raised rounded" src="img/examples/card-blog13.jpg" />
                </nuxt-link>
              </div>
              <h6 class="category text-info">Fashion</h6>
              <h3 class="card-title">
                <nuxt-link to="#pablo">Groupon Moves Into Flash Fashion</nuxt-link>
              </h3>
              <h5 class="card-description">
                More acquisitions for Groupon to widen the net of consumers
                using its platform for more than daily deals. Today it is
                announcing the acquisition of ideeli, a flash fashion retailer,
                for $43 million in...
              </h5>
              <nuxt-link to="#pablo" class="btn btn-success btn-round">Read More</nuxt-link>
            </card>
            <card type="blog" plain>
              <div class="card-image">
                <nuxt-link to="#pablo">
                  <img class="img img-raised rounded" src="img/examples/card-blog14.jpg" />
                </nuxt-link>
              </div>
              <h6 class="category text-success">Entertainment</h6>
              <h3 class="card-title">
                <nuxt-link to="#pablo">When music and technology collide</nuxt-link>
              </h3>
              <h5 class="card-description">
                Some might say that technology is killing the music industry.
                But if you look around, there’s a beautiful marriage there — the
                music industry is evolving every day, and artists are embracing
                technology in new and innovative ways...
              </h5>
              <nuxt-link to="#pablo" class="btn btn-success btn-round"> Read More</nuxt-link>
            </card>
          </div>
        </div>
      </div>
    </div>
    <!--     *********    END BLOGS 4      *********      -->
    <!--     *********    END BLOGS 5      *********      -->
    <div class="blogs-5" data-background-color="gray">
      <div class="container">
        <div class="row">
          <div class="col-md-10 ml-auto mr-auto">
            <h2 class="title">Latest Blogposts 5</h2>
            <div class="row">
              <div class="col-md-4">
                <div class="card card-blog">
                  <div class="card-image">
                    <nuxt-link to="#pablo">
                      <img class="img rounded" src="img/card-blog2.jpg" />
                    </nuxt-link>
                  </div>
                  <div class="card-body">
                    <h6 class="category text-success">Features</h6>
                    <h5 class="card-title">
                      That’s One Way To Ditch Your Passenger
                    </h5>
                    <p class="card-description">
                      As near as we can tell, this guy must have thought he was
                      going over backwards and tapped the rear...
                    </p>
                    <div class="card-footer">
                      <div class="author">
                        <img v-lazy="'img/julie.jpg'" alt="..." class="avatar img-raised" />
                        <span>Mike John</span>
                      </div>
                      <div class="stats stats-right">
                        <em class="now-ui-icons tech_watch-time"></em> 5 min
                        read
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-md-4">
                <div class="card card-blog">
                  <div class="card-image">
                    <nuxt-link to="#pablo">
                      <img class="img rounded" src="img/examples/card-blog18.jpg" />
                    </nuxt-link>
                  </div>
                  <div class="card-body">
                    <h6 class="category text-danger">Animals</h6>
                    <h5 class="card-title">
                      Shark Week: How to Watch It Like a Scientist
                    </h5>
                    <p class="card-description">
                      Just when you thought it was safe to turn on your
                      television, the Discovery Channel's "Shark Week"...
                    </p>
                    <div class="card-footer">
                      <div class="author">
                        <img v-lazy="'img/julie.jpg'" alt="..." class="avatar img-raised" />
                        <span>Mike John</span>
                      </div>
                      <div class="stats stats-right">
                        <em class="now-ui-icons tech_watch-time"></em> 5 min
                        read
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-md-4">
                <div class="card card-blog">
                  <div class="card-image">
                    <nuxt-link to="#pablo">
                      <img class="img rounded" src="img/examples/card-blog17.jpg" />
                    </nuxt-link>
                  </div>
                  <div class="card-body">
                    <h6 class="category text-success">Cars</h6>
                    <h5 class="card-title">
                      Who's Afraid of the Self-Driving Car?
                    </h5>
                    <p class="card-description">
                      It's been 60 years since the cover of Popular Mechanics
                      magazine gave us the promise of flying cars...
                    </p>
                    <div class="card-footer">
                      <div class="author">
                        <img v-lazy="'img/olivia.jpg'" alt="..." class="avatar img-raised" />
                        <span>Johanna Zmud</span>
                      </div>
                      <div class="stats stats-right">
                        <em class="now-ui-icons ui-2_favourite-28"></em> 2.4K
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--     *********    END BLOGS 5      *********      -->
  </div>
</template>
<script>
import { Card } from "@/components";
export default {
  components: {
    Card,
  },
};
</script>
<style>
</style>
