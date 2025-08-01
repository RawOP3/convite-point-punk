<style>
  body {
    background-color: black;
    color: white;
    font-family: 'Courier New', monospace;
    background-image: url('fundo-textura-punk.png'); /* opcional */
    background-size: cover;
    text-shadow: 1px 1px #ff0000;
  }
  h1 {
    font-size: 2.5rem;
    text-transform: uppercase;
    letter-spacing: 2px;
    border-bottom: 2px dashed red;
    display: inline-block;
    margin-bottom: 1rem;
  }
  img {
    border: 3px solid white;
    filter: contrast(120%) brightness(90%);
    max-width: 600px;
    width: 100%;
    transition: 0.2s ease;
  }
  img:hover {
    transform: rotate(-1deg) scale(1.01);
    filter: grayscale(0.8) contrast(130%);
  }
</style>
