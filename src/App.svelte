<script>
  export let name;
</script>

<style>
  section {
    margin: auto;
    max-width: 50vw;
  }
</style>

<main>

  <h1>Reasons why React components render</h1>
  <section>
    <h2>Parent component rendered</h2>
    <iframe
      src="https://codesandbox.io/embed/simple-react-rendering-example-2ylgh?codemirror=1&fontsize=14&hidenavigation=1&module=%2Fsrc%2FApp.js&theme=dark&view=preview&hidedevtools=1&
      hidenavigation=1&runonclick=1"
      style="width:100%; height:500px; border:0; border-radius: 6px;
      overflow:hidden;"
      title="Simple rendering example"
      allow="accelerometer; ambient-light-sensor; camera; encrypted-media;
      geolocation; gyroscope; hid; microphone; midi; payment; usb; vr;
      xr-spatial-tracking"
      sandbox="allow-autoplay allow-forms allow-modals allow-popups
      allow-presentation allow-same-origin allow-scripts" />
    <img src="/simple-render.png" />
    <img src="/skipped-render.png" />
  </section>
  <section>
    <h2>Context changed + parent rendered</h2>
    <iframe
      src="https://codesandbox.io/embed/naive-context-rendering-example-vq0sw?codemirror=1&fontsize=14&hidenavigation=1&module=%2Fsrc%2FApp.js&theme=dark&view=preview&hidedevtools=1&
      hidenavigation=1&runonclick=1"
      style="width:100%; height:500px; border:0; border-radius: 6px;
      overflow:hidden;"
      title="Simple rendering example"
      allow="accelerometer; ambient-light-sensor; camera; encrypted-media;
      geolocation; gyroscope; hid; microphone; midi; payment; usb; vr;
      xr-spatial-tracking"
      sandbox="allow-autoplay allow-forms allow-modals allow-popups
      allow-presentation allow-same-origin allow-scripts" />
    <img src="/context-render.png" />
  </section>
  <section>
    <h2>Same element Context changed</h2>
    <iframe
      src="https://codesandbox.io/embed/same-element-reference-kjcsc?codemirror=1&fontsize=14&hidenavigation=1&module=%2Fsrc%2FApp.js&theme=dark&view=preview&hidedevtools=1&
      hidenavigation=1&runonclick=1"
      style="width:100%; height:500px; border-radius: 6px; overflow:hidden;"
      title="Simple rendering example"
      allow="accelerometer; ambient-light-sensor; camera; encrypted-media;
      geolocation; gyroscope; hid; microphone; midi; payment; usb; vr;
      xr-spatial-tracking"
      sandbox="allow-autoplay allow-forms allow-modals allow-popups
      allow-presentation allow-same-origin allow-scripts" />
    <img src="/same-element-ref.png" />
  </section>
  <section>
    <h2>Meaningless memoization</h2>
    <iframe
      src="https://codesandbox.io/embed/meaningless-memoization-dzr1s?codemirror=1&fontsize=14&hidenavigation=1&module=%2Fsrc%2FApp.js&theme=dark&view=preview&hidedevtools=1&
      hidenavigation=1&runonclick=1"
      style="width:100%; height:500px; border-radius: 6px; overflow:hidden;"
      title="Simple rendering example"
      allow="accelerometer; ambient-light-sensor; camera; encrypted-media;
      geolocation; gyroscope; hid; microphone; midi; payment; usb; vr;
      xr-spatial-tracking"
      sandbox="allow-autoplay allow-forms allow-modals allow-popups
      allow-presentation allow-same-origin allow-scripts" />
    <img src="/meaningless-memo.png" />
  </section>
  <section>
    <h2>Meaningful memoization</h2>
    <iframe
      src="https://codesandbox.io/embed/meaningful-memoization-t0qle?codemirror=1&fontsize=14&hidenavigation=1&module=%2Fsrc%2FApp.js&theme=dark&view=preview&hidedevtools=1&
      hidenavigation=1&runonclick=1"
      style="width:100%; height:500px; border-radius: 6px; overflow:hidden;"
      title="Simple rendering example"
      allow="accelerometer; ambient-light-sensor; camera; encrypted-media;
      geolocation; gyroscope; hid; microphone; midi; payment; usb; vr;
      xr-spatial-tracking"
      sandbox="allow-autoplay allow-forms allow-modals allow-popups
      allow-presentation allow-same-origin allow-scripts" />
    <img src="/meaningful-memo.png" />
  </section>
  <section>
    <h2>Context and memoization</h2>
    <iframe
      src="https://codesandbox.io/embed/context-rendering-example-with-memo-iucib?codemirror=1&fontsize=14&hidenavigation=1&module=%2Fsrc%2FApp.js&theme=dark&view=preview&hidedevtools=1&
      hidenavigation=1&runonclick=1"
      style="width:100%; height:500px; border-radius: 6px; overflow:hidden;"
      title="Simple rendering example"
      allow="accelerometer; ambient-light-sensor; camera; encrypted-media;
      geolocation; gyroscope; hid; microphone; midi; payment; usb; vr;
      xr-spatial-tracking"
      sandbox="allow-autoplay allow-forms allow-modals allow-popups
      allow-presentation allow-same-origin allow-scripts" />
    <img src="/memo-context.png" />
  </section>
</main>
