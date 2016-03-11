---
layout: post
title:  "imgix Sandbox,<br>Image Inspector"
date:   2016-02-29 10:00:00
tags: design
headline: http://migimages.imgix.net/sandbox/sandbox-devices.png?fm=jpg&chromasub=444&bg=fafafa
thumbnail: http://migimages.imgix.net/sandbox/sandboxlogo.ai?page=2&fm=png8&bg=F0DBBB&fit=clamp&w=320&h=320&dpr=2&colorquant=48&pad=8&border=8,fff
thumbtitle: Imgix Sandbox
thumbdesc: UX/UI Design, Front End Styling
accentcolor: efd2aa
---

<section>
<p>imgix allows for image edits to be made via simple URL parameter operations, and can be difficult to construct or read the more operations get added. We needed a way to easily construct, breakdown, and share imgix URLs in a more meaningful way that can educate customers on how to use the imgix service.<p>

<p>Originally concieved as a URL inspector for imgix images, <a href="http://sandbox.imgix.com/">Sandbox</a> provides a simple text–based user interface to experiment with the imgix API. Feed any imgix URL into Sandbox to be deconstructed and tweaked. Sandbox URLs update automatically in the browser bar, so you can share exactly what you’re looking at by copying the URL.</p>
<p>With Sandbox, once difficult imgix operations like compositing, text formatting and color correction are made much easier.</p>
</section>

<section>
	<h2>imgix Operation Breakdowns</h2>
<p>When a user submits an imgix URL, Sandbox will break it down by parameter and value pairs displaying every imgix image operation on the image. This also gives the user the opportunity to adjust existing operations or add new ones.</p>
</section>

{% include picture.html img="https://migimages.imgix.net/sandbox/sandbox1.png?fm=pjpg&crop=top&q=80&chromasub=444&border=2,eee" alt="Sandbox Image Breakdown" caption="Sandbox breaks down imgix image URLs." %}

<section>
<h2>Details</h2>
<p>We wanted to make sure that sandbox worked on phones and tablets with a fluid and responsive layout. Sandbox also has a number of hinting, and specialized features, such as additional windows for compositing multiple images with a live preview.</p>
</section>


{% include picture.html img="https://migimages.imgix.net/sandbox/sandbox3.png?fm=pjpg&crop=top&q=80&chromasub=444&fit=fill&bg=fafafa&border=2,eee" alt="Sandbox shows comparisons" caption="Sandbox displays quality comparisons" %}

<!-- {% include thumb.html img="https://migimages.imgix.net/sandbox/sandbox-home.png?fm=pjpg&crop=top&q=80&chromasub=444&fit=fill&bg=fafafa" alt="imgix Sandbox Home" caption="Sandbox Home Screen URL input"%} -->

{% include picture.html img="https://migimages.imgix.net/sandbox/sandbox-hint.png?fm=pjpg&crop=entropy&q=80&chromasub=444&fit=fill&bg=fafafa&border=2,eee&rect=0,.08,.999,.998" alt="Documentation tool tips" %}

{% include picture.html img="https://migimages.imgix.net/sandbox/sandbox-hinting.png?fm=pjpg&crop=top,left&q=80&chromasub=444&fit=fill&bg=fafafa&border=2,eee" alt="Drop downs and param autofill" %}

<!-- {% include picture.html img="https://migimages.imgix.net/sandbox/sandbox-phone1.png?fm=png8&crop=top&q=80&chromasub=444&fit=fill&bg=fafafa&border=2,eee" alt="" %} -->

<!-- {% include picture.html img="https://migimages.imgix.net/sandbox/sandbox-phone3.png?fm=png8&crop=top&q=80&chromasub=444&fit=fill&bg=fafafa&border=2,eee" alt="" %} -->

{% include picture.html img="https://migimages.imgix.net/sandbox/sandbox-window.png?fm=pjpg&crop=top&q=80&chromasub=444&bg=fafafa&border=2,eee&fit=fill&bg=fafafa" alt="Composite and blend live editing popups" %}


<section>

<h2>Multiple Image Compositing</h2>
<p>
Use Sandbox to compose multiple images. When a parameter is set to blend, mark, or mask, an add button will appear. Click that button to open a pop-up window to customize that composite. Any changes you make in the pop-up will be reflected back to the original image.</p>
 <figure>

	<video id="sandbox2" width="640" poster="https://assets.imgix.net/sandbox/sandbox-mask.gif?frame=3" controls="" loop="" autoplay="" style="border:solid 1px #e3eaef;">
        <source src="https://assets.imgix.net/sandbox/sandbox-mask.mp4" type="video/mp4">
        <img src="https://assets.imgix.net/sandbox/sandbox-mask.gif" alt="image">
      </video>
 </figure>

<h2>Sandbox & imgix Documentation</h2>
<p>
Sandbox is deeply integrated with the imgix documentation. We believe great documentation doesn’t just tell you about a service, it shows you the service in action. Click on any image in the documentation to see an example loaded up in Sandbox. While in Sandbox, hover over the question mark next to any parameter to get a short description of what the parameter does.</p>
<figure>
 	<video id="sandbox1" width="640" poster="https://assets.imgix.net/sandbox/sandbox1.gif?frame=1" controls="" loop="" autoplay="" style="border:solid 1px #e3eaef;">
        <source src="https://assets.imgix.net/sandbox/sandbox-docs.mp4" type="video/mp4">
        <img src="https://assets.imgix.net/sandbox/sandbox1.gif" class="dpr-compat" alt="image">
      </video>
</figure>

</section>

{% include picture.html img="http://migimages.imgix.net/sandbox/sandboxlogo.ai?page=1&fm=png8&bg=fafafa&h=240" alt="Sandbox in Devices"%}

{% include calltoaction.html text="Try Sandbox" link="https://sandbox.imgix.com" title="Sandbox" %}
