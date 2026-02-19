
<style>
/* Wrapper */
.simple-marquee {
  width: 100%;
  overflow: hidden;
  background: #0b0b0b;
  padding: 12px 0;
}

/* Track */
.simple-marquee-track {
  display: flex;
  align-items: center;
  width: max-content;
  animation: simple-scroll 24s linear infinite;
}

/* Pause on hover */
.simple-marquee:hover .simple-marquee-track {
  animation-play-state: paused;
}

/* Item */
.simple-marquee-item {
  display: flex;
  align-items: center;
  gap: 12px;
  padding-right: 100px; /* space between items */
  color: #ffffff;
  font-size: 15px;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  white-space: nowrap;
}

/* 🔒 Force logo size */
.simple-marquee-item img {
  height: 20px !important;
  max-height: 20px !important;
  width: auto !important;
  max-width: none !important;
  display: block;
  object-fit: contain;
  opacity: 0.9;
}

/* Animation */
@keyframes simple-scroll {
  from {
    transform: translateX(100%);
  }
  to {
    transform: translateX(-100%);
  }
}
</style>

<div class="simple-marquee">
  <div class="simple-marquee-track">

    <div class="simple-marquee-item">
      <img src="https://your-site.com/logo.svg" alt="Logo" />
      <span>Connecting Ideas Across The Globe</span>
    </div>

    <div class="simple-marquee-item">
      <img src="https://your-site.com/logo.svg" alt="Logo" />
      <span>Innovation Without Borders</span>
    </div>

    <div class="simple-marquee-item">
      <img src="https://your-site.com/logo.svg" alt="Logo" />
      <span>Building Global Digital Experiences</span>
    </div>

  </div>
</div>

<style>
/* Wrapper */
.simple-marquee {
  width: 100%;
  overflow: hidden;
  background: #0b0b0b;
  padding: 12px 0;
}

/* Track */
.simple-marquee-track {
  display: flex;
  align-items: center;
  width: max-content;
  animation: simple-scroll 24s linear infinite;
}

/* Pause on hover */
.simple-marquee:hover .simple-marquee-track {
  animation-play-state: paused;
}

/* Item */
.simple-marquee-item {
  display: flex;
  align-items: center;
  gap: 12px;
  padding-right: 100px; /* space between items */
  color: #ffffff;
  font-size: 15px;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  white-space: nowrap;
}

/* 🔒 Force logo size */
.simple-marquee-item img {
  height: 20px !important;
  max-height: 20px !important;
  width: auto !important;
  max-width: none !important;
  display: block;
  object-fit: contain;
  opacity: 0.9;
}

/* Animation */
@keyframes simple-scroll {
  from {
    transform: translateX(100%);
  }
  to {
    transform: translateX(-100%);
  }
}
</style>

<div class="simple-marquee">
  <div class="simple-marquee-track">

    <div class="simple-marquee-item">
      <img src="https://your-site.com/logo.svg" alt="Logo" />
      <span>Connecting Ideas Across The Globe</span>
    </div>

    <div class="simple-marquee-item">
      <img src="https://your-site.com/logo.svg" alt="Logo" />
      <span>Innovation Without Borders</span>
    </div>

    <div class="simple-marquee-item">
      <img src="https://your-site.com/logo.svg" alt="Logo" />
      <span>Building Global Digital Experiences</span>
    </div>

  </div>
</div>