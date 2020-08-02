<p align="center">
<h1><b>नमस्ते / Hi / こんにちは</b></h1>
</p>

</br>

<img src="https://media.giphy.com/media/J3FxKYqrfD5Nxayo6p/giphy.gif"  width="800" height="275">

</br>

<a href="https://twitter.com/CleanScripting">
  <img align="left" width="40px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />
</a>

<a href="https://www.linkedin.com/in/vishnu-kumar-96bb79102">
  <img align="left"  width="40px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />
</a>

<a href="https://github.com/atkumarvishnu">
  <img align="left" alt="Github" width="40px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
</a>

<html>
  <head>
    <title>SVG Stroke Animation</title>
    <style>
        /* html {
            margin: 0;
            padding: 0;
            width: 100%;
        } */

        body {
            margin: 0;
            padding: 0;
            text-align: center;
            background:white;
            background-size: cover;
            height: 50vh;
            display: table;
        }

        .wrapper {
            position: absolute;
            top: 45%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 40%;
        }

        path {
            stroke: #000;
            fill: #000;
            stroke-dasharray: 1500;
            opacity: 10;
            animation: animate 3s cubic-bezier(0,0.23,1,.1);
        }

        @keyframes animate {
            0% {
                opacity: 0;
                fill: none;
                stroke-dashoffset: 1500;
            }

            30% {
                opacity: 10;
                fill: none;
                stroke-dashoffset: 1500;
            }

            90% {
                fill: rgba(255,255,255,0);
            }

            100% {
                opacity: 10;
                fill: rgba(255,255,255,1);
                stroke-dashoffset: 0;
            }
        }

    </style>
  </head>
  <body>
    <div class="wrapper">
      <svg
        version="1.1"
        id="Layer_1"
        xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink"
        x="0px"
        y="0px"
        viewBox="0 0 569 348"
        style="enable-background: new 0 0 569 348;"
        xml:space="preserve"
      >
        <style type="text/css">
          .st0 {
            fill: #000;
            stroke: #000;
            stroke-width: 3;
            stroke-miterlimit: 10;
          }
        </style>
        <g>
          <path
            class="st0"
            d="M59.62,67.52l-43.5,258l263.1-310.5c1.2-1.6,2.7-2.7,4.5-3.3c1.8-0.6,3.6-1,5.4-1.2c3.4,0,6.45,1.35,9.15,4.05
   c2.7,2.7,4.05,5.75,4.05,9.15c0,3-1,5.8-3,8.4c-0.2,0-0.3,0.1-0.3,0.3l-286.5,310.5c-0.8,0.8-1.9,1.2-3.3,1.2
   c-1.2,0-2.2-0.45-3-1.35c-0.8-0.9-1.2-1.95-1.2-3.15l32.1-275.4c0.4-3,1.65-5.4,3.75-7.2c2.1-1.8,4.65-2.7,7.65-2.7
   c3.2,0,5.85,1.15,7.95,3.45c2.1,2.3,3.15,4.85,3.15,7.65V67.52z"
          />
          <path
            class="st0"
            d="M266.31,205.52l-0.9,1.8l-2.7,6.3c-1,3.2-2.1,6.15-3.3,8.85c-1.2,2.7-2.2,5.45-3,8.25l-2.7,8.7l-0.9,4.2
   c-0.6,1.6-1.05,3.2-1.35,4.8c-0.3,1.6-0.65,3.2-1.05,4.8l4.5-5.7l5.7-7.2l5.4-7.5l7.8-11.1l4.2-5.7l3.6-5.7l2.7-3.9
   c1.4-2,2.75-4.25,4.05-6.75c1.3-2.5,3.35-3.75,6.15-3.75c1.8,0,3.25,0.6,4.35,1.8c1.1,1.2,1.65,2.5,1.65,3.9
   c-0.2,2.2-1.15,4.25-2.85,6.15c-1.7,1.9-3.15,3.65-4.35,5.25l-8.1,10.8l-5.4,7.5l-13.5,18.6l-5.4,7.8l-5.7,7.5l-3,3.9l-1.2,1.2
   c-0.2,0-0.3,0.05-0.3,0.15c0,0.1-0.1,0.15-0.3,0.15l-0.6,0.6c-0.2,0-0.3,0.05-0.3,0.15c0,0.1-0.1,0.15-0.3,0.15l-0.6,0.3
   c-0.4,0.4-0.75,0.55-1.05,0.45c-0.3-0.1-0.55-0.05-0.75,0.15l-3.6-0.6c-1-0.4-1.7-0.8-2.1-1.2c-0.4-0.4-0.9-0.9-1.5-1.5l-0.6-1.2
   c-0.4-0.4-0.6-0.8-0.6-1.2c0-0.4-0.1-0.7-0.3-0.9l-0.6-1.8c0-1.6-0.1-3.05-0.3-4.35c-0.2-1.3-0.3-2.65-0.3-4.05l0.9-9.9l0.9-9.3
   l4.2-28.2l1.2-9.3v-0.3c0.4-2.8,1.7-5.2,3.9-7.2c2.2-2,4.8-3,7.8-3c3.2,0,5.95,1.15,8.25,3.45c2.3,2.3,3.45,5.15,3.45,8.55
   C267.51,202.22,267.11,203.92,266.31,205.52z M257.01,151.52l0.9-10.2c0.4-3.2,1.75-5.8,4.05-7.8c2.3-2,4.85-3,7.65-3
   c3.4,0,6.25,1.2,8.55,3.6c2.3,2.4,3.45,5.2,3.45,8.4c0,1-0.1,1.9-0.3,2.7c-0.2,0.8-0.4,1.5-0.6,2.1l-4.5,9.6
   c-1,1.8-2.35,3.15-4.05,4.05c-1.7,0.9-3.45,1.35-5.25,1.35c-3.4,0-5.9-1.15-7.5-3.45C257.81,156.57,257.01,154.12,257.01,151.52z"
          />
          <path
            class="st0"
            d="M303.51,203.72c0,5,0.7,9.95,2.1,14.85c1.4,4.9,3.1,9.75,5.1,14.55c1.8-2.6,3.95-5.9,6.45-9.9
   c2.5-4,5.05-7.95,7.65-11.85c2.6-3.9,5.05-7.25,7.35-10.05c2.3-2.8,4.05-4.2,5.25-4.2c1.8,0,3.25,0.6,4.35,1.8
   c1.1,1.2,1.65,2.5,1.65,3.9c0,1.4-0.55,3.15-1.65,5.25c-1.1,2.1-2.4,4.3-3.9,6.6c-1.5,2.3-3.05,4.55-4.65,6.75
   c-1.6,2.2-2.9,4.1-3.9,5.7c-2.2,3.4-4.45,6.7-6.75,9.9c-2.3,3.2-4.65,6.4-7.05,9.6c0.2,0.8,0.3,1.6,0.3,2.4c0,0.8,0,1.6,0,2.4
   c0,7.6-2.2,14.3-6.6,20.1c-4.4,5.8-9.8,10.7-16.2,14.7l-3.3,2.1c-0.4,0-0.85,0.2-1.35,0.6c-0.5,0.4-0.95,0.6-1.35,0.6l-0.9,0.6
   c-1.2,0.4-2.1,0.6-2.7,0.6c-1.4,0-2.75-0.55-4.05-1.65c-1.3-1.1-1.95-2.55-1.95-4.35c0-0.6,0.2-1.3,0.6-2.1v-0.3
   c1.6-4,3.6-7.8,6-11.4s4.8-7.1,7.2-10.5l7.8-11.4l-1.5-3.6l-1.8-3c-3.4-6-6.5-12.55-9.3-19.65c-2.8-7.1-4.2-14.65-4.2-22.65
   c0-3.2,0.6-6.8,1.8-10.8l1.5-3c1-1.6,2.75-3.55,5.25-5.85c2.5-2.3,5.75-3.45,9.75-3.45c2.6,0,5.3,0.8,8.1,2.4l4.2,3
   c2,1.4,3,3.6,3,6.6c0,2.4-1.1,4.7-3.3,6.9l-8.7,6.3C303.61,202.62,303.51,203.12,303.51,203.72z M304.71,198.32l0.3-0.6
   c-0.2,0-0.3,0.1-0.3,0.3l-0.3,0.6L304.71,198.32z"
          />
          <path
            class="st0"
            d="M332.61,199.82c1.8-4,3.8-8.05,6-12.15c2.2-4.1,4.2-8.15,6-12.15l12.6-23.7l2.4-3.9l1.8-5.4
   c1.6-4.2,3-8.6,4.2-13.2c1.2-4.6,2.9-9,5.1-13.2l2.4-4.8l2.1-3.9l2.4-2.7l0.3-0.6l1.8-1.5l1.5-1.2l2.1-0.9c0.4,0,0.85-0.1,1.35-0.3
   c0.5-0.2,0.95-0.3,1.35-0.3h2.4c0.2,0,0.6,0.1,1.2,0.3c0.6,0.2,1,0.2,1.2,0c0.8,0.4,1.6,0.8,2.4,1.2c0.6,0.4,1.25,0.85,1.95,1.35
   c0.7,0.5,1.25,0.95,1.65,1.35l1.8,2.4c1,1.2,1.55,2.45,1.65,3.75c0.1,1.3,0.15,2.15,0.15,2.55v1.8c0,0.6-0.1,1.2-0.3,1.8
   c-0.2,0.6-0.3,1.2-0.3,1.8l-1.2,3.3c-0.2,1-0.45,1.85-0.75,2.55c-0.3,0.7-0.65,1.55-1.05,2.55l-6.9,12.6
   c-1.2,2.2-2.5,4.45-3.9,6.75c-1.4,2.3-2.7,4.35-3.9,6.15c-2.2,5.2-4.1,10.5-5.7,15.9c-1.6,5.4-3.3,10.7-5.1,15.9l-10.5,30.6
   c1.4-2.6,2.8-5,4.2-7.2c1.4-2.2,2.9-4.5,4.5-6.9l5.4-7.2c0.2-0.4,0.9-1.2,2.1-2.4l1.2-1.5c0.2,0,0.5-0.2,0.9-0.6l1.2-0.9
   c0.4-0.2,0.75-0.4,1.05-0.6c0.3-0.2,0.65-0.4,1.05-0.6l1.5-0.6h1.8c0-0.2,0.1-0.3,0.3-0.3h0.9l0.6,0.3h0.3
   c2.2,0,3.85,0.65,4.95,1.95c1.1,1.3,1.75,2.05,1.95,2.25l0.6,1.2l1.2,2.7c0,1,0.05,1.85,0.15,2.55c0.1,0.7,0.15,1.35,0.15,1.95v1.8
   c0,1-0.05,2-0.15,3c-0.1,1-0.15,2.1-0.15,3.3l-1.8,11.1c-0.4,2-1.05,4.15-1.95,6.45c-0.9,2.3-1.25,4.25-1.05,5.85l23.1-30.9
   c0.8-1.2,2.1-1.8,3.9-1.8c1.4,0,2.55,0.5,3.45,1.5c0.9,1,1.35,2.2,1.35,3.6c0,1.2-0.3,2.2-0.9,3l-41.4,56.1
   c-1.4,1.4-2.8,2.1-4.2,2.1c-1.4,0-2.6-0.5-3.6-1.5c-1-1-1.5-2.2-1.5-3.6c0-1,0.05-2.15,0.15-3.45c0.1-1.3,0.35-2.45,0.75-3.45
   l0.3-2.7l2.1-12.9l2.7-17.4c-1.6,2.2-3.1,4.45-4.5,6.75c-1.4,2.3-2.8,4.55-4.2,6.75l-22.5,36.6c-1.2,1.8-2.5,3.9-3.9,6.3
   c-1.4,2.4-2.85,4.7-4.35,6.9c-1.5,2.2-2.9,4.05-4.2,5.55c-1.3,1.5-2.45,2.25-3.45,2.25c-1.4,0-2.55-0.45-3.45-1.35
   c-0.9-0.9-1.35-1.85-1.35-2.85c0-0.2,0.05-0.4,0.15-0.6c0.1-0.2,0.15-0.4,0.15-0.6v-0.9c0.2-0.8,0.3-1.55,0.3-2.25
   c0-0.7,0.2-1.45,0.6-2.25l0.6-4.5c1.8-10.6,3.95-20.9,6.45-30.9c2.5-10,4.95-20.3,7.35-30.9l2.4-10.5l-3.3,3.3
   c-0.8,1-2,1.5-3.6,1.5c-1.2,0-2.35-0.45-3.45-1.35c-1.1-0.9-1.65-2.05-1.65-3.45C332.01,201.82,332.21,201.02,332.61,199.82z"
          />
          <path
            class="st0"
            d="M435.2,192.92l-12,24.6l1.5-2.1c2-2.4,4.1-4.8,6.3-7.2c2.2-2.4,4.4-4.7,6.6-6.9l3.6-3.6c0.4,0,0.8-0.3,1.2-0.9
   l2.7-1.5l1.8-0.6l0.6-0.3c0-0.2,0.1-0.3,0.3-0.3h0.9c0.4-0.2,1.2-0.3,2.4-0.3h0.9c0.6,0.4,1.2,0.6,1.8,0.6s1.3,0.2,2.1,0.6l1.5,1.2
   c1.4,1,2.35,2.05,2.85,3.15c0.5,1.1,0.75,1.75,0.75,1.95l1.2,4.2l0.3,5.7c0,1,0,1.85,0,2.55c0,0.7-0.1,1.55-0.3,2.55l-1.5,13.8
   l-1.2,9l0.6-0.9c2.8-3.8,5.3-7.55,7.5-11.25c2.2-3.7,4.5-7.45,6.9-11.25l6.3-12l1.8-4.2c1.4-2.4,3.4-3.6,6-3.6
   c1.8,0,3.3,0.65,4.5,1.95c1.2,1.3,1.8,2.75,1.8,4.35c0,0.6-0.1,1.2-0.3,1.8c-0.2,0.6-0.3,1.2-0.3,1.8l-9.6,15.9l-9.9,15.6l-4.8,7.8
   c-0.6,1-1.4,2.1-2.4,3.3c-1,1.2-1.7,2-2.1,2.4l-1.8,2.4l-2.4,1.8c-0.2,0.4-0.7,0.8-1.5,1.2l-3.6,1.5c-0.8,0-1.4-0.1-1.8-0.3
   c-0.4-0.2-0.9-0.3-1.5-0.3l-1.5-0.6l-2.4-2.4l-1.5-3.6l-0.9-4.2c0-1.2-0.1-2.5-0.3-3.9c-0.2-1.4-0.3-2.6-0.3-3.6l-1.2-18.6v-0.3
   l-7.2,7.2l-6,6.3c-4,4.6-8.1,9.05-12.3,13.35c-4.2,4.3-8.2,8.85-12,13.65l-7.8,9.9l-2.1,3.3c0,0.2-0.1,0.4-0.3,0.6l-0.9,1.5
   l-1.5,1.2c-0.4,0.4-0.85,0.75-1.35,1.05c-0.5,0.3-1.45,0.45-2.85,0.45c-1.2,0-2.55-0.6-4.05-1.8s-2.25-2.8-2.25-4.8v-1.2l0.3-0.9
   c0-0.2,0.1-0.3,0.3-0.3v-0.6l0.6-0.9l0.3-0.6l0.9-1.2l0.9-1.5l0.9-2.1l3.3-8.4c4.6-11.4,8.65-22.9,12.15-34.5
   c3.5-11.6,6.65-23.1,9.45-34.5c0.8-2.8,2.2-5.05,4.2-6.75c2-1.7,4.4-2.55,7.2-2.55c3.4,0,6.25,1.2,8.55,3.6
   c2.3,2.4,3.45,5.2,3.45,8.4c0,1-0.1,1.8-0.3,2.4L435.2,192.92z"
          />
          <path
            class="st0"
            d="M500.3,206.72l-0.9,2.1l-3,6l-6.9,16.2c-1,3-1.95,5.85-2.85,8.55c-0.9,2.7-1.65,5.55-2.25,8.55l-1.8,8.4
   l-0.6,3.9v3.9c0.4-0.2,0.75-0.4,1.05-0.6c0.3-0.2,0.65-0.5,1.05-0.9l2.4-3c1.6-1.6,2.8-3.2,3.6-4.8l3.3-5.4
   c2.2-3.8,4.1-7.75,5.7-11.85c1.6-4.1,3.1-8.25,4.5-12.45l2.7-8.4l0.9-4.2l0.3-1.5l0.6-1.8v-1.2c0.4-2.8,1.55-5.1,3.45-6.9
   c1.9-1.8,4.25-2.7,7.05-2.7c3.6,0,6.35,1.25,8.25,3.75c1.9,2.5,2.85,5.65,2.85,9.45c0,3.6-0.3,6.4-0.9,8.4
   c-0.6,2-1.2,3.95-1.8,5.85c-0.6,1.9-1.2,4.2-1.8,6.9c-0.6,2.7-0.9,6.75-0.9,12.15v2.1l1.2-1.5c0.4-0.4,0.75-0.75,1.05-1.05
   c0.3-0.3,0.65-0.65,1.05-1.05l3.9-5.1l1.8-2.4c3-4.6,5.65-9.25,7.95-13.95c2.3-4.7,4.75-9.65,7.35-14.85c0.2-0.4,0.3-0.7,0.3-0.9
   c0-0.2,0.2-0.5,0.6-0.9l0.9-3l0.3-0.6c0-1.6,0.7-2.85,2.1-3.75c1.4-0.9,2.7-1.35,3.9-1.35c1.6,0,3.05,0.6,4.35,1.8
   c1.3,1.2,1.95,2.6,1.95,4.2c0,1.4-0.3,2.4-0.9,3l-0.9,1.8l-2.7,4.5l-10.2,17.4l-6.9,11.7l-3.6,5.7c-0.8,1-1.5,1.95-2.1,2.85
   c-0.6,0.9-1.4,1.85-2.4,2.85l-2.4,3l-1.8,1.2c-0.4,0.6-1.05,1.15-1.95,1.65c-0.9,0.5-1.75,0.85-2.55,1.05l-1.8,0.6h-2.4
   c-1.2-0.4-2.4-0.95-3.6-1.65c-1.2-0.7-2.2-2.05-3-4.05l-1.5-4.2l-0.9-3.6l-1.5,2.1l-5.1,7.8l-5.7,7.8l-6.9,7.5
   c-1,1-2.15,1.95-3.45,2.85c-1.3,0.9-2.65,1.55-4.05,1.95l-2.1,0.6c-0.4,0-0.7,0.1-0.9,0.3h-2.4c-1.6,0-3-0.45-4.2-1.35
   s-2.1-1.85-2.7-2.85l-1.2-1.8c-1-1.6-1.5-3.5-1.5-5.7c0-2.2,0-4.2,0-6l0.9-9.6l0.9-4.8c0.2-1.6,0.4-3.1,0.6-4.5
   c0.2-1.4,0.5-2.9,0.9-4.5l4.5-27.3l0.9-4.8l0.3-3.3l0.3-1.8c0.4-2.8,1.7-5.15,3.9-7.05c2.2-1.9,4.7-2.85,7.5-2.85
   c3.4,0,6.2,1.15,8.4,3.45c2.2,2.3,3.3,4.95,3.3,7.95C502.1,203.32,501.5,205.32,500.3,206.72z"
          />
        </g>
      </svg>
    </div>
  </body>
</html>

