# Quail-browser

This is a simple utility built upon the excellent work of quail-js.  

## Use

I like to trigger this utility manually since it can take a second or two to run through a large
group of tests.  

First, wrap any component you'd like to test with a parent container, classed .example.

    <div class="example">
      <p> Is this code accessible?</p>
    </div>

Next, add a trigger button to your page.

    <button id="test-accessibility">Accessibility Audit</button>

Done.
