<template>
  <div class="resume-wrapper">
    <article class="paper">
      <header>
        <div class="header-content">
          <div class="header-text">
            <p>
              Yi Yue
            </p>
            <p class="res-subtitle">Software Engineer</p>
          </div>
        </div>
      </header>
      <div class="content-wrapper">
        <!-- CONTACT -->
        <section class="content">
          <div class="row">
            <div class="content-cat">
              Contact
            </div>
            <div class="content-text">
              <ul>
                <li>Website</li>
                <li>lokyi.github.io</li>
              </ul>
              <ul>
                <li>Email</li>
                <li>roy.yi.yue@gmail.com</li>
              </ul>
              <ul>
                <li>Phone</li>
                <li>(765) 237-2016</li>
              </ul>
            </div>
          </div>
        </section>

        <section class="content">
          <div class="row">
            <div class="content-cat big-text">
              Work  Experience
              <p>2014-07-14 till today</p>
            </div>
            <div class="content-text work-listing education-listing">
              <p style="margin-top:2.4em;">
                <strong>Software Engineer</strong>
                at <strong>Andrew Wilder, Inc:</strong>
              </p>
              <p>Andrew Wilder develops a proprietary software system called Innovative Metrics, </p>
              <p class="highlight">Currently leading a full-stack development team, working on making server rendered react app for several lead generation services</p>
              <p class="highlight">Developed a content management system for advertisements and landing pages using Kendo UI, React.js, and Flux in the front-end, and Node.js, Express, MySQL and Redis in the back-end</p>
              <p class="highlight">Developed an ad performance tracking system in Node.js to monitor impressions, clicks, and transactions. Pivoted summary reports are generated in real-time to optimize ad placement</p>
            </div>
          </div>
        </section>

        <section class="content work-content">
          <div class="row">
            <div class="content-cat big-text">
              <p>2013-06-14 till 2013-12-18</p>
            </div>
            <div class="content-text work-listing education-listing">
              <p>
                <strong>Intern Software Engineer</strong>
                at <strong>Second Sight Medical Product:</strong>
              </p>
              <p class="highlight">Prototyped a web application to provide patient testing and examining environment on the browser. The application uses Node.js on the backend and serves static web pages where tests are rendered in canvas elements. Test results are plotted with Flot.</p>
              <p class="highlight">Developed image processing scripts in MatLab to characterize performances of video cameras under various settings.</p>
            </div>
          </div>
        </section>

        <section class="content">
          <div class="row">
            <div class="content-cat big-text">
              Education
              <p>2012-08-20 till 2014-06-10</p>
            </div>
            <div class="content-text work-listing education-listing">
              <p class="heading" style="margin-top:2.35em;">University of Southern California</p>
              <p class="highlight">
                Master:
                <i>Wireless Health Technology </i>
              </p>
            </div>
          </div>
        </section>

        <section class="content education-content">
          <div class="row">
            <div class="content-cat big-text">
              <p>2008-08-20 till 2012-06-10</p>
            </div>
            <div class="content-text work-listing education-listing">
              <p class="heading">Purdue University</p>
              <p class="highlight">
                Bachelor:
                <i>Electrical Engineering </i>
              </p>
            </div>
          </div>
        </section>

        <section class="content">
          <div class="row">
            <div class="content-cat big-text">
              Awards
              <p>3rd Place IBM Watson Case Study Competition</p>
              <p style="margin-top:0.25em;">2014-04-07</p>
            </div>
            <div class="content-text work-listing">
              <strong><p class="heading">IBM</p></strong>
              <p class="highlight">Proposed to apply IBM Watson in assisted living and home environments to improve personalized care quality, increase service capacity and also reduce cost.</p>
            </div>
          </div>
        </section>

        <section class="content">
          <div class="row">
            <div class="content-cat">
              Skills
            </div>
            <div class="content-text skills-listing">
              <p>
                <span class="name">
                  <strong>
                    Web Development:
                  </strong>
                </span>
                HTML, Pug, CSS, LESS, Javascript, React, Redux, Flux, Node.js, MySQL, Redis, ElasticSearch, Amazon Web Services
              </p>
            </div>
          </div>
        </section>

        <!-- PROFILES -->
        <section class="content profiles">
          <div class="row">
            <div class="content-cat">
              Profiles
            </div>
            <div class="content-text profiles-listing">
              <ul>
                <li>
                  <a href="https://github.com/lokyi" target="_blank">
                    Github
                  </a>
                </li>
                <li>
                  <a href="https://www.linkedin.com/in/yi-yue/" target="_blank">
                    LinkedIn
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </section>

      </div>
    </article>
  </div>
</template>

<style>
body, html {
  padding-top:2.5em;
  margin:0;
  background-color:#fafafa;
}
.note {
  display:block;
  position: absolute;
  top:10px;
  left:10px;
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 0.6em;
}
.new {
  background-color: #81C784;
  border: 1px solid #757575;
  padding: 1px;
  border-radius: 4px;
}
/* Header */
header {
  width:100%;
  vertical-align: middle;
  text-align: center;
}
.header-content {
  display: inline-block;
}
.pic {
  margin: 0 auto;
  margin-top:-2.5em;
  border-radius:10em;
  height:4em;
  width:4em;
  border: 2px solid #e0e0e0;
  transition : all 0.5s linear;
}
@keyframes wiggle {
  0%   {
    transform: rotate(0deg);
  }
  25%  {
    transform: rotate(-30deg);
  }
  50%  {
    transform: rotate(15deg);
  }
  100% {
    transform: rotate(0deg);
  }
}
.pic:hover {
  /*Webkit fix*/
  -webkit-transform: translateZ(0);
  cursor:pointer;
  -webkit-animation: wiggle 0.7s cubic-bezier(0.6, -0.28, 0.735, 0.045);
}
.header-text {
  margin-top:0.5em;
  margin-left:1em;
}
header p {
  text-align:center;
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  margin:0;
  color: #212121;
}
.first-name {
   font-size: 1.05em;
}
.res-subtitle {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  padding-top:.3em;
  font-size:0.55em;
  font-weight:500;
  color: #424242;
}
/* Information */
.paper {
  margin: 0 auto;
  margin-bottom:1em;
  background-color:white;
  width:60%;
  padding:0.5em 0 0.5em 0;
  border-top: 1px solid #e0e0e0;
  border-left: 1px solid #e0e0e0;
  border-right: 1px solid #e0e0e0;
  border-bottom: 3px solid #e0e0e0;
  border-radius:3px;
}
@media(max-width:992px) {
  .paper {
    width:80%;
  }
}
/* Content Part */
.content-wrapper {
  padding-right:7.25%;
}
.content {
  display:table;
  width:100%;
  padding-top:1.5em;
  /*border-top: 1px solid #eeeeee;*/
}
.content:last-child {
  margin-bottom: 2em;
}
body > div > article > div > section:last-child {
  padding-bottom:1.5em;
}
.row {
    display:table-row;
}
.row div {
    display:table-cell;
}
.content-cat {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-variant:small-caps;
  font-weight:300;
  letter-spacing: 1px;
  color: #212121;
  font-size:0.975em;
  text-align:center;
  vertical-align:middle;
  padding-left:6.66%;
  width:30%;
}
.content-cat p {
  font-size:0.55em;
  font-weight:600;
  margin-bottom:0;
}
.content-text {
  border-left:1px solid #e0e0e0;
  transition: border 0.66s ease-in;
}
.big-text {
  vertical-align:top;
}
.content-text ul {
  padding:0;
  margin:0;
  margin-top:0.15em;
  width:85%;
  margin-left:1.5em;
}
.content-text ul:last-child {
  margin-bottom:0.5em;
}
.content-text ul li {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size:0.7em;
  display:inline-block;
}
.content-text ul li:first-child {
  width:35%;
  color: #424242;
  font-weight:600;
}
.content-text ul li a, div.content-text.work-listing.education-listing > p > strong > a {
  text-decoration: none;
  color: #0277bd;
}
.content-text ul li a:hover {
  color:#4fc3f7;
}
.work-listing p {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size:0.7em;
  color: #424242;
  margin-left:2em;
  margin-top:0.45em;
  margin-bottom: 0.45em;
}
div.content-text.work-listing.education-listing > p:nth-child(2) {
  margin-top:0.25em;
}
.work-listing .highlight {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size:0.7em;
  font-weight:400;
  color: #424242;
  margin-left:3.25em;
  padding-left:0.5em;
  border-left:1px solid #e0e0e0;
}
.education-listing > .heading {
  font-weight:600;
  margin-top:0.75em;
  margin-left:2em;
}
.education-listing > .highlight {
  margin-left:3.25em;
}
.highlight {
  transition: border .33s ease-in;
}
.profiles-listing ul li, .profiles-listing ul li:first-child {
  width:32%;
  font-weight: normal;
}
.work-content, .education-content {
  padding-top: .75em;
}
section.content.education-content > div > div.content-cat {
  vertical-align: top;
}
div.content-text.skills-listing > p {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size:0.7em;
  font-weight:400;
  margin-left: 2em;
  margin-top: 0.45em;
  margin-bottom: 0.45em;
}
div.content-text.skills-listing > p > {
  color:#212121;
}
@media screen and (max-width: 600px) {
  body, html {
    padding-top: 30px;
  }
  .paper {
    width:95%;
  }
  .row div {
    display: block;
  }
  .content-cat {
    width: 100%;
  }
  .content-text ul li {
    width: 100%;
  }
  .content-text ul li:first-child {
    width: 100%;
  }
  .education-listing > .highlight {
    margin-left: 30px;
  }
}

@media print {
  body, html {
    background-color: white;
    padding-top: 1.5em;
  }
  .paper {
    width:100%;
    border: 0;
    padding-top: 0;
  }
  header p {
    font-size: 1.3em;
  }
  .res-subtitle {
    font-size: 0.7em;
  }
  .header-pic {
    float:left;
  }
  .profiles {
    display:none;
  }
  .content {
    page-break-inside:avoid;
    page-break-after:auto;
  }
  .header-text {
    float:left;
    margin-top: -1.6em;
  }
  .content-wrapper > .content:first-child {
    padding-top: 2em;
  }
  .content:last-child {
    padding-bottom: 0;
  }
  .content-cat {
    width:33%;
    color:black;
    text-align: left;
  }
  .content-cat p {
    font-size:0.6em;
    font-weight: 600;
  }
  header p, .content-text, .work-listing p, .content-text ul li:first-child, .work-listing .highlight, .content-text.skills-listing > ul > li > .highlight {
    color:black;
  }
  .content-text.skills-listing > ul > li span, .res-subtitle {
    color:#212121;
  }
  .content-text ul:last-child {
    margin-bottom: 0.25em;
  }
  .content-text ul li:first-child {
    width:50%;
  }
  .profiles-listing ul li:first-child {
    width:32%;
  }
  div.content-text.skills-listing > ul > li {
    width:33%;
  }
  .work-listing p {
    margin-bottom: 0.1em;
  }
  div.content-text.skills-listing > ul > li > p {
    margin-top: 0.4em;
    margin-bottom: 0.5em;
  }
  div.content-text.skills-listing > ul > li {
    padding-left: 1.5em;
  }
  div.content-text.skills-listing > ul > li:first-child {
    padding-left: 2em;
  }
  .note {
    display:none;
  }
  .content-text:hover {
    border-left:1px solid #eeeeee;
  }
  .content-text ul li a:hover {
    color:#4fc3f7;
  }
  .highlight:hover, .content-text.skills-listing > ul > li > .highlight:hover {
    border-left:1px solid #eeeeee;
  }
  .big-text {
    padding-top: 0;
  }
}
</style>