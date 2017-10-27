---
layout: post
title:  "imgix Page Weight Tool, Performance Measurement Utiliy"
date:   2016-02-29 09:00:00
categories: product design
tags: design
headline: http://migimages.imgix.net/scale/scale-screens1.png?fm=jpg&chromasub=444&bg=fafafa
thumbnail: http://migimages.imgix.net/scale/page_weight_logo_mark.ai?fm=png8&fit=crop&page=1&colorquant=128&bg=fafafa
thumbtitle: imgix Page Weight 
thumbdesc: UX/UI Design, Front End Styling
accentcolor: 14c5f7
published: false
---

<section>
<p>imgix Scale is a utility in the spirit of Google Page Speed to measure page weight and room for improvement for image optimization. A user enters in a URL, and the result is a report on image optimization, and potential size.</p>
<p>The project doubles as a sales tool for imgix as it educates users on what images are currently bogging down their site, as well as their current rankings against other sites as reported by the top sites in the Internet Archive.</p>

</section>

{% include picture.html img="http://migimages.imgix.net/scale/scale-home-devices.png?fm=jpg&chromasub=444&bg=fafafa" alt="imgix Scale Home" %}

{% include picture.html img="http://migimages.imgix.net/scale/scale7.png?fm=pjpg&bg=fff&crop=top&fit=fill&bg=fafafa&border=2,eee" alt="" %}

{% include picture.html img="http://migimages.imgix.net/scale/scale-screens.png?fm=jpg&chromasub=444&bg=fafafa" alt="" %}

{% include picture.html img="http://migimages.imgix.net/scale/scale_icons.ai?fm=png8&bg=fafafa&crop=middle&h=240&fit=crop" alt="" %}

{% include picture.html img="http://migimages.imgix.net/scale/scale-graph.png?fm=png8&border=2,eee" alt="" %}

{% include picture.html img="http://migimages.imgix.net/scale/pageweight-header.png?fm=png8&border=1,eee" alt="" %}

{% include picture.html img="http://migimages.imgix.net/scale/page_weight_logo_mark.ai?fm=png8&bg=fafafa&crop=middle&fit=crop&page=2" alt="" %}

<section>
<h3>Dyanmic OG Share Images</h3>
<p>
We wanted a way to enhance the share experience of the page weight tool, and make the most of the imgix platform while we were at it. We came up with the idea of creating dymaic Open Graph images, that displayed the title, and URL of the page being reported on.</p><p>Internally, as we worked on the tool, we spent a lot of time sharing the report URLs, and figured it would be a moment of suprise an delight for users: seeing the custom OG image displaying the custom content show up. The dynamic images are generated primarily for slack, facebook, reddit and twitter standard OG image sizes. 
</p>
<p>
<img src="https://assets.imgix.net/page-weight/canvas.png?marky=28&fm=png8&txtfont64=RGluIEFsdGVybmF0ZQ&by=280&txtclip=end%2Cellipsis&txtpad=60&txtclr=00adea&txtsize=24&txtalign=left%2Cbottom&txt64=aHR0cDovL3d3dy5ueXRpbWVzLmNvbS9pbnRlcmFjdGl2ZS8yMDE2LzAxLzA3L3RyYXZlbC9wbGFjZXMtdG8tdmlzaXQuaHRtbD9fcj0w&markx=40&ba=bottom&bx=50&bm=normal&blend64=aHR0cHM6Ly9hc3NldHMuaW1naXgubmV0L350ZXh0P3R4dDY0PVNXNGdUaTVHTGt3dUxDQkVaV1Z3YkhrZ1JteGhkMlZrSUVOdmJtTjFjM05wYjI0Z1VtVnpaV0Z5WTJnZ0ppQlVhV1Z6SUhSdklFSnBaeUJVYjJKaFkyTnZJQzBnVkdobElFNWxkeUJaYjNKcklGUnBiV1Z6JnR4dGNscj1mZmYmdz0xMTAwJnR4dGZvbnQ2ND1SRWxPSUVGc2RHVnlibUYwWlN4Q2IyeGsmdHh0c2l6ZT00OCZ0eHRhbGlnbj1ib3R0b20maD0yNjA&fit=crop&h=630&w=1200&mark64=aHR0cHM6Ly9hc3NldHMuaW1naXgubmV0L3BhZ2Utd2VpZ2h0L3BhZ2Vfd2VpZ2h0X3JlcG9ydF9sb2dvX21hcmsuYWk_aXhsaWI9cmItMS4xLjAmbWFya3k9MzAmbWFya3g9MzAmbWFya2FsaWduPXRvcCUyQ2xlZnQmbWFyazY0PWFIUjBjSE02THk5aGMzTmxkSE11YVcxbmFYZ3VibVYwTDNCeVpYTnphMmwwTDJsdFoybDRMWEJ5WlhOemEybDBMbkJrWmo5a2NISTlNU1ptYlQxd2JtY21jR0ZuWlQwMCZ3PTEzNjAmYmc9MDAyMTJiMzImZml0PWZpbGwmaD02NDAmZm09cG5n&bg=212b32&markscale=60">
<!-- <br><br>
<img src="https://assets.imgix.net/page-weight/canvas.png?markscale=60&bg=212b32&mark64=aHR0cHM6Ly9hc3NldHMuaW1naXgubmV0L3BhZ2Utd2VpZ2h0L3BhZ2Vfd2VpZ2h0X3JlcG9ydF9sb2dvX21hcmsuYWk_aXhsaWI9cmItMS4xLjAmbWFya3k9MzAmbWFya3g9MzAmbWFya2FsaWduPXRvcCUyQ2xlZnQmbWFyazY0PWFIUjBjSE02THk5aGMzTmxkSE11YVcxbmFYZ3VibVYwTDNCeVpYTnphMmwwTDJsdFoybDRMWEJ5WlhOemEybDBMbkJrWmo5a2NISTlNU1ptYlQxd2JtY21jR0ZuWlQwMCZ3PTEzNjAmYmc9MDAyMTJiMzImZml0PWZpbGwmaD02NDAmZm09cG5n&w=1200&h=630&fit=crop&blend64=aHR0cHM6Ly9hc3NldHMuaW1naXgubmV0L350ZXh0P2g9MjYwJnR4dGFsaWduPWJvdHRvbSZ0eHRzaXplPTcyJnR4dGZvbnQ2ND1SRWxPSUVGc2RHVnlibUYwWlN4Q2IyeGsmdz0xMTAwJnR4dGNscj1mZmYmdHh0NjQ9YVZCaFpDQlFjbThnTFNCQmNIQnNaUQ&bm=normal&bx=50&ba=bottom&markx=40&txt64=aHR0cDovL3d3dy5hcHBsZS5jb20vaXBhZC1wcm8vP2NpZD13d2EtdXMta3dnLWlwYWQmY3A9cHJv&txtalign=left%2Cbottom&txtsize=24&txtclr=00adea&txtpad=60&txtclip=end%2Cellipsis&by=280&txtfont64=RGluIEFsdGVybmF0ZQ&fm=png8&marky=28"> -->
</p>

{% include picture.html img="http://migimages.imgix.net/scale/pageweight-fb.png?fm=png8&bg=fafafa&crop=middle&fit=max&border=1,eee" alt="" %}

{% include picture.html img="http://migimages.imgix.net/scale/pageweight-slack.png?fm=png8&bg=fafafa&crop=middle&fit=max&border=1,eee" alt="" %}

</section>








