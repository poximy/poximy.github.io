<h1>
  > portfolio<span class="blink">_</span>
</h1>
<main>
  <h2 class="typewriter">I’m a 21 year old full-stack developer</h2>
  <article>
    <section>
      <h3>> Skills<span class="blink">_</span></h3>
      <ul class="skills-list">
        <li>
          Programming Languages: Python, Javascript, TypeScript, HTML, CSS
        </li>
        <li>DataBases: MongoDB, PostgreSQL</li>
        <li>Frameworks: Svelte, React, FastAPI, TailwindCSS</li>
        <li>Tools: Linux / Unix & Git</li>
        <li>Languages: English & Spanish fluent</li>
      </ul>
    </section>
    <section>
      <h3>> Projects<span class="blink">_</span></h3>
      <ul class="project-list">
        <li>
          <p class="project-title">
            URL Shortener
            <a href="https://url-svelte.netlify.app">Demo</a>
            -
            <a href="https://github.com/erickzv/url-shortener-frontend-svelte"
              >Source code</a
            >
          </p>
          <p>
            Build the frontend and backend, the frontend is built with the
            svelte framework using typescript, on the other side the backend is
            made in python using fastapi, this includes authentication (jwt),
            all connected to mongodb.
          </p>
        </li>
        <li>
          <p class="project-title">
            Apple Rumors Web Scrapper
            <a href="https://apple-rumors-erickzv.vercel.app">Demo</a>
            -
            <a href="https://github.com/erickzv/apple_rumors">Source code</a>
          </p>
          <p>
            Created a web scrapper that finds apple related rumors, built with
            nextjs using typescript for the frontend, with requests and
            beautifulsoup library for web scrapping using fastapi.
          </p>
        </li>
        <li>
          <p class="project-title">
            Work Project (Reser’s tools worksheet)
            <a href="https://reser.netlify.app">Demo</a>
            -
            <a href="https://github.com/erickzv/reser-tools">Source code</a>
          </p>
          <p>
            Developed a worksheet to calculate averages for my past workplace,
            found it very repetitive for me and my coworkers to calculate this
            every day saving us time. Built with svelte and typescript.
          </p>
        </li>
        <li>
          <p class="project-title">
            Crypto Price Tracker
            <a href="https://crypto-tracker-erickzv.netlify.app/">Demo</a>
            -
            <a href="https://github.com/erickzv/crypto-price-tracker">
              Source code
            </a>
          </p>
          <p>
            Created a crypto currency price tracking tool to monitor current
            price of the most popular crypto currencies, created with reactjs
            written in typescript, axios with the coin gecko API for the data.
          </p>
        </li>
      </ul>
    </section>
    <section>
      <h3>> Contact --erick<span class="blink">_</span></h3>
      <ul class="contact-list">
        <li>-erickzv21@gmail.com</li>
        <li>-<a href="https://www.linkedin.com/in/erick-zv/">LinkedIn</a></li>
        <li>-<a href="https://github.com/poximy">Github</a></li>
      </ul>
    </section>
  </article>
</main>

<style>
  h1 {
    font-size: 4rem;
  }

  h3 {
    font-size: 2rem;
  }

  main {
    max-width: min-content;
    font-family: "IBM Plex Mono", monospace;
  }

  section {
    margin-bottom: 2rem;
  }

  .skills-list {
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }

  ul {
    list-style: none;
    padding: 0;
    margin: 0;
  }

  a {
    color: white;
  }

  .project-title {
    font-size: 1.2rem;
  }

  .project-list {
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
  }

  .contact-list {
    font-size: 1.2rem;
    display: flex;
    justify-content: center;
    gap: 1.5rem;
  }

  /* Animations */
  .blink {
    animation: blink 1s infinite step-end;
  }

  @keyframes blink {
    from,
    to {
      opacity: 0;
    }
    50% {
      opacity: 1;
    }
  }

  .typewriter {
    overflow: hidden;
    border-right: 0.15em none #fff;
    white-space: nowrap;
    margin: 0 auto;
    letter-spacing: 0.15em;
    animation: typing 3s steps(40, end), blink-caret 1s step-end infinite;
  }

  @keyframes typing {
    from {
      width: 0;
    }
    to {
      width: 100%;
    }
  }

  @keyframes blink-caret {
    from,
    to {
      border-color: transparent;
    }
    50% {
      border-color: #fff;
    }
  }
</style>
