# LendEDU Maps

A plugin created to replace two others to have the freedom and be able to hone down the simplicity of creating a map and supporting HTML.  Map created with simple shortcode.

## Getting Started

Simply add the `[state_map]` shortcode on any page/post to create a beautifully styled map with generated labels and tooltips from your HTML file.

## How-To

#### Step-by-step
a. Create a full html file in web storm
1. Open [this Example State HTML file](../example-state.html)
    1. copy all information into your full html file in web storm 
2. Open your excel file
3. copy state information and paste into tableizer
4. Copy from tableizer `<tbody>....</tbody>` -> that's all, nothing else!
5. Paste `<tbody>...` info into your new full html file in web storm
    1. into the same `<tbody` that is currently there
6. Open [this Example State Tooltip Html File](../example-state-tooltip.html)
7. Add your state information for the tooltip, and copy/paste that into your full html file 
8. Now you have all needed information 
    1. there are a couple changes needed at this point
        1. ensure opening div contains state abbreviation ie. `<div id="AL" class="state">
        ...content ... </div>`
        2. ensure the tooltip html follows the example: ie.
        `<div class="tooltip">
        <span id="tooltip-span-AL"><strong>Rank:</strong>7
        <strong>Average Debt:</strong> $31,257
        <strong>Change from ’15:</strong> +1.81%
        <strong>Proportion with Debt:</strong> 51%
        </span></div>`
        ensure that the state abbreviation is included: ie. `<span id="tooltip-span-AL">...`
 9. Slack Ray if you need anything
 
## Authors

* **Ray Flores** - *Initial work* - [LendEDU](https://github.com/mclenhard/lendedu-plugins/tree/master/lendedu-maps)
