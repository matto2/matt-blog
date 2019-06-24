---
layout: layouts/post.njk
title: Paintings
tags:
  - about

templateClass: tmpl-post
---

I used to paint a lot. Here's a few pieces - hope to add some new stuff here soon.

<div class="gallery">
<div class="grid">

  <a class="module" href="">
    <div>
      <img src="/img/anini_beach.jpg" alt="Anini beach">
      <br>
      <p>Anini beach</p>
    </div>
  </a>

  <a class="module" href="">
    <div>
      <img src="/img/barrel_view.jpg" alt="The view of surfing in the barrel">
      <br>
      <p>Barrel view</p>
    </div>
  </a>

 <a class="module" href="">
    <div>
      <img src="/img/polihale.jpg" alt="Polihale">
      <br>
      <p>Polihale</p>
    </div>
  </a> 

   <a class="module" href="">
    <div>
      <img src="/img/tunnels_beach.jpg" alt="Tunnels beach">
      <br>
      <p>Tunnels beach</p>
    </div>
  </a> 

  <a class="module" href="">
    <div>
      <img src="/img/beanhollow5_3560.jpg" alt="Cove at Bean Hollow">
      <br>
      <p>Cove at Bean Hollow</p>
    </div>
  </a>

  <a class="module" href="">
    <div>
      <img src="/img/breaching_in_the_bay.jpg" alt="Breaching Whale">
      <br>
      <p>Breaching Whale</p>
    </div>
  </a>

   <a class="module" href="">
    <div>
      <img src="/img/china_cove_rock.jpg" alt="Rock at Chine Cove">
      <br>
      <p>Rock at Chine Cove</p>
    </div>
  </a>

   <a class="module" href="">
    <div>
      <img src="/img/dolphins.jpg" alt="Dolphins">
      <br>
      <p>Dolphins</p>
    </div>
  </a>

   <a class="module" href="">
    <div>
      <img src="/img/fullers_3558.jpg" alt="Big Sur surf spot">
      <br>
      <p>Big Sur Surf Spot</p>
    </div>
  </a>

   <a class="module" href="">
    <div>
      <img src="/img/getchells.jpg" alt="Getchells cove">
      <br>
      <p>Getchells Cove</p>
    </div>
  </a>

   <a class="module" href="">
    <div>
      <img src="/img/its_3559.jpg" alt="Its Beach">
      <br>
      <p>Its Beach</p>
    </div>
  </a>

   <a class="module" href="">
    <div>
      <img src="/img/itsbeach_cave_3571.jpg" alt="Its Beach Cove">
      <br>
      <p>Its Beach Cove</p>
    </div>
  </a>

   <a class="module" href="">
    <div>
      <img src="/img/lane_moon_3568.jpg" alt="Moon over Steamer Lane">
      <br>
      <p>Moon over Steamer Lane</p>
    </div>
  </a>

   <a class="module" href="">
    <div>
      <img src="/img/lemon_3578.jpg" alt="Lemon still life">
      <br>
      <p>Lemon still life</p>
    </div>
  </a>

   <a class="module" href="">
    <div>
      <img src="/img/sweet_view.jpg" alt="Sweet view">
      <br>
      <p>Sweet view</p>
    </div>
  </a>

   <a class="module" href="">
    <div>
      <img src="/img/the_lane_at_sunset.jpg" alt="The Lane at sunset">
      <br>
      <p>The Lane at sunset</p>
    </div>
  </a>

   <a class="module" href="">
    <div>
      <img src="/img/off_the_lip_3.jpg" alt="Off the lip">
      <br>
      <p>Off the lip</p>
    </div>
  </a>

   <a class="module" href="">
    <div>
      <img src="/img/pipe.jpg" alt="Pipeline">
      <br>
      <p>Pipeline</p>
    </div>
  </a>

   <a class="module" href="">
    <div>
      <img src="/img/sunset__jet_700px.jpg" alt="Sunset and jet">
      <br>
      <p>Sunset and jet</p>
    </div>
  </a> 

   <a class="module" href="">
    <div>
      <img src="/img/waves_moon_3569.jpg" alt="Waves and moon">
      <br>
      <p>Waves and moon</p>
    </div>
  </a>    


<br>
  <!-- <a href="usabilitytesting">
    <div class="module">
      <img src="/img/usertest1.png">
      <br>
      <p>Usability Testing</p>
    </div>
  </a> -->

  <!-- <div class="module">4</div>
  <div class="module">5</div>
  <div class="module">6</div>
  <div class="module">7</div>
  <div class="module">8</div>
  <div class="module">9</div>
  <div class="module">10</div>
  <div class="module">11</div>
  <div class="module">12</div>
  <div class="module">13</div>
  <div class="module">14</div>
  <div class="module">15</div> -->
</div>
</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>
<script type="text/javascript" src="../dist/simple-lightbox.js"></script>
<script>
	$(function(){
		var $gallery = $('.gallery a').simpleLightbox();
		$gallery.on('show.simplelightbox', function(){
			console.log('Requested for showing');
		})
		.on('shown.simplelightbox', function(){
			console.log('Shown');
		})
		.on('close.simplelightbox', function(){
			console.log('Requested for closing');
		})
		.on('closed.simplelightbox', function(){
			console.log('Closed');
		})
		.on('change.simplelightbox', function(){
			console.log('Requested for change');
		})
		.on('next.simplelightbox', function(){
			console.log('Requested for next');
		})
		.on('prev.simplelightbox', function(){
			console.log('Requested for prev');
		})
		.on('nextImageLoaded.simplelightbox', function(){
			console.log('Next image loaded');
		})
		.on('prevImageLoaded.simplelightbox', function(){
			console.log('Prev image loaded');
		})
		.on('changed.simplelightbox', function(){
			console.log('Image changed');
		})
		.on('nextDone.simplelightbox', function(){
			console.log('Image changed to next');
		})
		.on('prevDone.simplelightbox', function(){
			console.log('Image changed to prev');
		})
		.on('error.simplelightbox', function(e){
			console.log('No image found, go to the next/prev');
			console.log(e);
		});
	});
</script>

<ul class="arrows">
  <li><a href="{{ '/about' | url }}">&#8592; Back</a></li>
</ul>