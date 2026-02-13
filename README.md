<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Email Archive</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <div class="year">2017</div>
    <!-- <div class="title">Optional title</div> -->
  </header>

  <img
  src="images/2017.jpg"
  alt=""
  class="email-image"
>

  <a class="next" href="email-02.html">→</a>

  <script>
    document.addEventListener("keydown", function (e) {
      if (e.key === "ArrowRight") {
        const next = document.querySelector(".next");
        if (next) window.location.href = next.href;
      }
      if (e.key === "ArrowLeft") {
        const prev = document.querySelector(".prev");
        if (prev) window.location.href = prev.href;
      }
    });
  </script>

</body>
</html>
{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 body \{\
  margin: 0;\
  background: white;\
\}\
\
header \{\
  margin: 30px;\
\}\
\
.year \{\
  font-family: Arial, Helvetica, sans-serif;\
  font-size: 13px;\
  letter-spacing: 1px;\
  opacity: 0.5;\
\}\
\
.title \{\
  font-family: Arial, Helvetica, sans-serif;\
  font-size: 14px;\
  margin-top: 6px;\
  opacity: 0.7;\
\}\
\
.email-image \{\
  display: block;\
  max-width: 90%;\
  margin: 0 auto 120px auto;\
\}\
\
.next,\
.prev \{\
  position: fixed;\
  bottom: 30px;\
  font-size: 24px;\
  text-decoration: none;\
  color: black;\
  opacity: 0.4;\
  font-family: Arial, Helvetica, sans-serif;\
\}\
\
.next \{ right: 30px; \}\
.prev \{ left: 30px; \}\
\
.next:hover,\
.prev:hover \{\
  opacity: 1;\
\}\
}
