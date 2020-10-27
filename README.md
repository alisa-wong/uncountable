# uncountable
Interactive data visualization take home assignment for Uncountable

Run `python -m SimpleHTTPServer 8000` (Python 2) or `python -m http.server` (Python 3). Open localhost:8000.

Current features:
- Select an input + output to generate scatterplot
- See all inputs for a certain input category distinguished by color
- Hover over point to get input + output information for that point
  - Other points for the same experiment are highlighted
- Click on a point to retrieve full experiment information

To be improved:
- Input color selection: Carbon Black High Grade is too dark, cannot read text in Experiment panel
- Hover text
  - Cuts off towards right side of svg (required more calculation)
  - Does not appear above all other elements
  - Background color to be more readable
- Interactivity
  - Create line across points for selected experiment to show which is selected + keep opacity as 1 when selected
  - When an experiment is still selected and the user is not hovering over any points, have non-selected points have lowered opacity
- Make it clearer to the user that when clicking on a point, full experiment detail is displayed

Features that were not implemented:
- Be able to select which inputs are shown if there are multiple in the category
- Be able to select two experiments to compare full details
