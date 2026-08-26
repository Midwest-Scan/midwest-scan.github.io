---
layout: about
title: about
permalink: /
subtitle: From raw signals to understandable systems.

profile:
  align: right
  image: nathan_barnes.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p class="founder-caption"><strong>Nathan Barnes</strong><br>Founder, Midwest Scan</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  .midwest-home {
    font-size: 1.02rem;
    line-height: 1.65;
  }

  .post > .post-header {
    margin-bottom: 1.8rem;
  }

  .post > .post-header .post-title {
    max-width: 42rem;
    margin: 0;
    font-size: clamp(2.1rem, 4.35vw, 2.85rem);
    font-weight: 400;
    line-height: 1.14;
    letter-spacing: -0.025em;
  }

  .post > .post-header .desc {
    display: none;
  }

  #navbar .midwest-navbar-brand {
    display: flex;
    align-items: center;
    padding: 0;
    text-decoration: none;
  }

  #navbar .midwest-navbar-lockup {
    display: block;
    width: 9.5rem;
    height: auto;
  }

  #navbar .midwest-anchor-link {
    white-space: nowrap;
  }

  #selected-work,
  #about-the-founder,
  #contact {
    scroll-margin-top: 5.5rem;
  }

  .midwest-home .home-intro p {
    margin-bottom: 1.15rem;
  }

  .midwest-home .home-focus {
    margin: 1.35rem 0 0;
  }

  .midwest-home .home-section {
    clear: both;
    padding-top: 1.75rem;
  }

  .midwest-home .section-heading {
    margin: 0 0 1.35rem;
  }

  .midwest-home .section-intro {
    max-width: 42rem;
    margin: -0.6rem 0 1.6rem;
  }

  .midwest-home .work-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(min(100%, 15rem), 1fr));
    gap: 1.75rem;
  }

  .midwest-home .work-item {
    padding-top: 1.1rem;
    border-top: 1px solid var(--global-divider-color);
  }

  .midwest-home .work-item h3 {
    margin: 0 0 0.65rem;
    font-size: 1.3rem;
    line-height: 1.3;
    overflow-wrap: anywhere;
  }

  .midwest-home .work-item h3 a {
    color: inherit;
    text-decoration-color: var(--global-theme-color);
    text-decoration-thickness: 1px;
    text-underline-offset: 0.18em;
  }

  .midwest-home .work-item h3 a:hover {
    color: var(--global-theme-color);
  }

  .midwest-home .work-item p {
    margin: 0;
  }

  .midwest-home .founder-section {
    margin-top: 3rem;
    padding-top: 2.25rem;
    border-top: 1px solid var(--global-divider-color);
  }

  .midwest-home .founder-section p {
    max-width: 48rem;
    margin-bottom: 0;
  }

  .midwest-home .contact-section {
    margin-top: 3rem;
    padding-top: 2.25rem;
    border-top: 1px solid var(--global-divider-color);
  }

  .midwest-home .contact-intro {
    max-width: 42rem;
    margin-bottom: 1.5rem;
  }

  .midwest-home .contact-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(min(100%, 12rem), 1fr));
    gap: 1.25rem 2rem;
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .midwest-home .contact-list li {
    display: flex;
    flex-direction: column;
    gap: 0.2rem;
  }

  .midwest-home .contact-label {
    font-size: 0.75rem;
    font-weight: 600;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    opacity: 0.65;
  }

  .post .profile .founder-caption {
    margin-top: 0.75rem;
    font-family: Roboto, Helvetica, Arial, sans-serif;
    font-size: 0.88rem;
    line-height: 1.45;
  }

  footer .midwest-footer {
    display: flex;
    flex-direction: column;
    gap: 0.15rem;
    line-height: 1.5;
  }

  footer .midwest-footer-credit {
    font-size: 0.82rem;
    opacity: 0.68;
  }

  footer .midwest-footer-credit a {
    color: inherit;
    text-decoration: underline;
    text-decoration-thickness: 1px;
    text-underline-offset: 0.15em;
  }

  footer .midwest-footer-credit a:hover {
    color: var(--global-theme-color);
  }

  @media (min-width: 576px) {
    .post .profile {
      width: 24%;
      margin-left: 2.5rem;
    }

    .post .profile img {
      width: 100%;
      aspect-ratio: 4 / 5;
      object-fit: cover;
      object-position: center 22%;
    }
  }

  @media (max-width: 575px) {
    #navbar .midwest-navbar-lockup {
      width: 8.4rem;
    }

    .post .profile {
      margin-bottom: 2rem;
    }

    .post > .post-header .post-title {
      font-size: clamp(2rem, 9.5vw, 2.35rem);
    }

    .midwest-home .home-section {
      padding-top: 1.75rem;
    }
  }
</style>

<div class="midwest-home">
  <div class="home-intro">
    <p>
      Midwest Scan is an independent technical research and development studio founded and operated by Nathan Barnes in Minnesota. Its work
      centers on satellite data systems, remote sensing, RF signal processing, scientific software, and technical visualization, with an
      emphasis on practical tools and underdocumented systems.
    </p>

    <p>
      Current work includes METEOR LRPT analysis, satellite telemetry, remote-sensing instrument research, and software that makes specialized
      data easier to inspect and understand.
    </p>

    <p class="home-focus"><strong>Current focus:</strong> satellite data · remote sensing · RF/DSP · scientific software</p>

  </div>

  <section id="selected-work" class="home-section" aria-labelledby="selected-work-heading">
    <h2 id="selected-work-heading" class="section-heading">Selected work</h2>
    <p class="section-intro">Open-source tools for creating, analyzing, and working with METEOR M2-x LRPT data.</p>
    <div class="work-grid">
      <article class="work-item">
        <h3>
          <a href="https://github.com/Midwest-Scan/METEOR-LRPT-Encoder">METEOR-LRPT-Encoder <span aria-hidden="true">↗</span></a>
        </h3>
        <p>
          Encodes three grayscale channel images into METEOR M2-x LRPT CADUs or a transmission-ready PRBS/NRZ-M bitstream, with GNU Radio
          modulation and swath-distortion tools.
        </p>
      </article>

      <article class="work-item">
        <h3>
          <a href="https://github.com/Midwest-Scan/METEOR-LRPT-QF-Extract">METEOR-LRPT-QF-Extract <span aria-hidden="true">↗</span></a>
        </h3>
        <p>
          Extracts per-segment JPEG quality factors from LRPT CADUs and turns them into per-channel TIFF maps, JSON statistics, and a color
          heatmap.
        </p>
      </article>

      <article class="work-item">
        <h3><a href="https://github.com/Midwest-Scan/MeteorThumb">MeteorThumb <span aria-hidden="true">↗</span></a></h3>
        <p>
          A native Windows thumbnail provider and companion tools that validate LRPT CADUs, decode MSU-MR channels, correct the swath, and
          generate RGB previews directly in Explorer.
        </p>
      </article>
    </div>

  </section>

  <section id="about-the-founder" class="founder-section" aria-labelledby="about-the-founder-heading">
    <h2 id="about-the-founder-heading" class="section-heading">About the founder</h2>
    <p>
      Midwest Scan was founded by Nathan Barnes, an independent developer and technical researcher focused on satellite reception, signal
      analysis, and practical scientific software. The studio grew from earlier work in 3D scanning, photogrammetry, and visualization and now
      applies that same interest in acquiring, reconstructing, and interpreting data to satellite and remote-sensing systems.
    </p>
  </section>

  <section id="contact" class="contact-section" aria-labelledby="contact-heading">
    <h2 id="contact-heading" class="section-heading">Contact</h2>
    <p class="contact-intro">For technical collaboration, software questions, or project inquiries, get in touch.</p>
    <ul class="contact-list">
      <li>
        <span class="contact-label">Email</span>
        <span>{% al_email_protect_link site.data.socials.email %}</span>
      </li>
      <li>
        <span class="contact-label">GitHub</span>
        <a href="https://github.com/Midwest-Scan">github.com/Midwest-Scan</a>
      </li>
      <li>
        <span class="contact-label">Phone</span>
        <a href="tel:+16124054555">(612) 405-4555</a>
      </li>
    </ul>
  </section>
</div>

<script>
  (() => {
    const heroTitle = document.querySelector(".post-header .post-title");
    if (heroTitle) heroTitle.textContent = "From raw signals to understandable systems.";

    const footerContainer = document.querySelector("footer .container");
    if (footerContainer && footerContainer.dataset.midwestEnhanced !== "true") {
      const footer = document.createElement("div");
      footer.className = "midwest-footer";

      const copyright = document.createElement("div");
      copyright.textContent = `© ${new Date().getFullYear()} Midwest Scan LLC.`;

      const credit = document.createElement("div");
      credit.className = "midwest-footer-credit";

      const jekyllLink = document.createElement("a");
      jekyllLink.href = "https://jekyllrb.com/";
      jekyllLink.textContent = "Jekyll";

      const alFolioLink = document.createElement("a");
      alFolioLink.href = "https://github.com/alshedivat/al-folio";
      alFolioLink.textContent = "al-folio";

      credit.append("Built with ", jekyllLink, " and ", alFolioLink, ".");
      footer.append(copyright, credit);
      footerContainer.replaceChildren(footer);
      footerContainer.dataset.midwestEnhanced = "true";
    }

    const navbar = document.getElementById("navbar");
    const container = navbar?.querySelector(".container");
    const menu = navbar?.querySelector(".navbar-menu-list");

    if (!navbar || !container || !menu || navbar.dataset.midwestEnhanced === "true") return;

    const brand = document.createElement("a");
    brand.className = "navbar-brand midwest-navbar-brand";
    brand.href = "{{ '/' | relative_url }}";
    brand.setAttribute("aria-label", "Midwest Scan home");

    const lockup = document.createElement("img");
    lockup.className = "midwest-navbar-lockup";
    lockup.alt = "Midwest Scan";
    lockup.width = 152;
    lockup.height = 32;

    const darkLockup = "{{ '/assets/img/midwest-scan-lockup-dark.svg' | relative_url }}";
    const lightLockup = "{{ '/assets/img/midwest-scan-lockup-light.svg' | relative_url }}";
    const colorScheme = window.matchMedia("(prefers-color-scheme: dark)");

    const updateLockup = () => {
      let storedTheme = "system";
      try {
        storedTheme = localStorage.getItem("theme") || storedTheme;
      } catch {
        // Keep following the visitor's system preference if storage is unavailable.
      }

      const theme = document.documentElement.dataset.themeSetting || storedTheme;
      const useDarkLockup = theme === "dark" || (theme !== "light" && colorScheme.matches);
      lockup.src = useDarkLockup ? darkLockup : lightLockup;
    };

    updateLockup();
    brand.append(lockup);
    container.prepend(brand);

    new MutationObserver(updateLockup).observe(document.documentElement, {
      attributes: true,
      attributeFilter: ["data-theme-setting"],
    });
    colorScheme.addEventListener?.("change", updateLockup);

    menu.querySelectorAll(":scope > .nav-item").forEach((item) => item.remove());

    const themeToggle = menu.querySelector(":scope > .toggle-container");
    const links = [
      ["Work", "#selected-work"],
      ["About", "#about-the-founder"],
      ["Contact", "#contact"],
    ];

    links.forEach(([label, href]) => {
      const item = document.createElement("li");
      item.className = "nav-item";

      const link = document.createElement("a");
      link.className = "nav-link midwest-anchor-link";
      link.href = href;
      link.textContent = label;
      link.addEventListener("click", () => {
        const collapse = navbar.querySelector(".navbar-collapse-main");
        const toggle = navbar.querySelector(".navbar-toggler-main");
        if (collapse?.classList.contains("show")) toggle?.click();
      });

      item.append(link);
      menu.insertBefore(item, themeToggle);
    });

    navbar.dataset.midwestEnhanced = "true";
  })();
</script>
