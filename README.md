  <body>
    <h1>[FreeCodeCamp] Data Visualization Projects</h1>
    <h2>Visualize Data with a Scatterplot Graph</h2>
    <strong>Objective: </strong>Build an app that is functionally similar to
    this: <a href="https://codepen.io/freeCodeCamp/full/bgpXyK.">https://codepen.io/freeCodeCamp/full/bgpXyK.</a>
    <p align="justify"></p>
    <p align="justify">Fulfill the below user stories and get all of the tests to pass. Use
      whichever libraries or APIs you need. Give it your own personal style.</p>
    <p align="justify">You can use HTML, JavaScript, CSS, and the D3 svg-based visualization
      library. The tests require axes to be generated using the D3 axis
      property, which automatically generates ticks along the axis. These ticks
      are required for passing the D3 tests because their positions are used to
      determine alignment of graphed elements. You will find information about
      generating axes at <a href="https://github.com/d3/d3/blob/master/API.md#axes-d3-axis">https://github.com/d3/d3/blob/master/API.md#axes-d3-axis</a>.
      Required (non-virtual) DOM elements are queried on the moment of each
      test. If you use a frontend framework (like Vue for example), the test
      results may be inaccurate for dynamic content. We hope to accommodate them
      eventually, but these frameworks are not currently supported for D3
      projects.</p>
    <p align="justify"><strong>User Story #1</strong>: I can see a title element that has a
      corresponding<strong> id="title"</strong>.</p>
    <p align="justify"><strong>User Story #2</strong>: I can see an x-axis that has a
      corresponding <strong>id="x-axis"</strong>.</p>
    <p align="justify"><strong>User Story #3</strong>: I can see a y-axis that has a
      corresponding <strong>id="y-axis"</strong>.</p>
    <p align="justify"><strong>User Story #4</strong>: I can see dots, that each have a class of
      <strong>dot</strong>, which represent the data being plotted.</p>
    <p align="justify"><strong>User Story #5</strong>: Each dot should have the properties <strong>data-xvalue
        </strong>and <strong>data-yvalue </strong>containing their
      corresponding <strong>x</strong> and <strong>y</strong> values.</p>
    <p align="justify"><strong>User Story #6:</strong> The <strong>data-xvalue</strong> and <strong>data-yvalue
        </strong>of each dot should be within the range of the actual data and
      in the correct data format. For <strong>data-xvalue</strong>, integers
      (full years) or <strong>Date </strong>objects are acceptable for test
      evaluation. <strong>For data-yvalue (minutes)</strong>, use <strong>Date
      </strong>objects.</p>
    <p align="justify"><strong>User Story #7</strong>: The <strong>data-xvalue</strong> and its
      corresponding dot should align with the corresponding point/value on the
      x-axis.</p>
    <p align="justify"><strong>User Story #8</strong>: The <strong>data-yvalue</strong> and its
      corresponding dot should align with the corresponding point/value on the
      y-axis.</p>
    <p align="justify"><strong>User Story #9</strong>: I can see multiple tick labels on the
      y-axis with <strong>%M:%S</strong> time format.</p>
    <p align="justify"><strong>User Story #10</strong>: I can see multiple tick labels on the
      x-axis that show the year.</p>
    <p align="justify"><strong>User Story #11</strong>: I can see that the range of the x-axis
      labels are within the range of the actual x-axis data.</p>
    <p align="justify"><strong>User Story #12</strong>: I can see that the range of the y-axis
      labels are within the range of the actual y-axis data.<br>
      <br>
      <strong>User Story #13</strong>: I can see a legend containing descriptive
      text that has <strong>id="legend"</strong>.</p>
    <p align="justify"><strong>User Story #14</strong>: I can mouse over an area and see a
      tooltip with a corresponding <strong>id="tooltip"</strong> which displays
      more information about the area.</p>
    <p align="justify"><strong>User Story #15</strong>: My tooltip should have a <strong>data-year</strong>
      property that corresponds to the <strong>data-xvalue</strong> of the
      active area.</p>
    <p align="justify">Here is the dataset you will need to complete this project: <a href="https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/cyclist-data.json">https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/cyclist-data.json</a></p>
    <p align="justify">You can build your project by using this CodePen template and clicking
      Save to create your own pen. Or you can use this CDN link to run the tests
      in any environment you like: <a href="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js">https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js</a></p>
    <p align="justify">Once you're done, submit the URL to your working project with all its
      tests passing.</p>
    <p align="justify"><strong>Solution:</strong> <a href="https://github.com/cwchan0212/fcc-scatterplot">Source</a>
      | <a href="https://codepen.io/cwchan0212/pen/MWVJrmx">demo@codepen</a></p>
    
  </body>
