---
title: "Green Hydrogen: The Economic Case For Being Less Efficient"
draft: false
---


### I.

Multiple EU countries are currently making large investments in the production of green hydrogen. The argument often seems to consist of one or both of the following points[^1].
- The transition away from fossil fuels is necessary, not only in energy systems (where we may be able to rely on renewables) but also in steel, fertilizer and other industries, where hydrocarbons seem to be an inexorable part of the chain.
- Renewable energy sources are intermittent, meaning that hydrogen can be used to seasonally stabilize grid load.
    
To a relative amateur such as my self, these seem like solid arguments, which makes it all the more puzzling to me that most seem to go about it in a deeply counterintuitive way. At least if you take a look at the numbers.

The name of the game for these firms, seems to be efficiency. How can we use fancy techniques and prescious metals in our electrolyzers to squeeze out just a bit more hydrogen for the same amount of power. 

Nature sets a floor - water electrolysis requires about 39 kWh per kg of hydrogen. A modern electrolyzer like the  [HyProvide X-1200](https://www.greenhydrogensystems.com/electrolysers/hyprovide-x-series-6mw-modular-electrolyser) ends up actually using 51.9 kWh/kg, implying an efficiency of around 75%[^2] . I would argue that we would be much better off focusing on creating less efficient ways of producing hydrogen.

### II.

To make green hydrogen economically viable, the magic number everyone talks seems to be [around €2/kg](https://energiwatch.dk/Energinyt/Politik___Markeder/article17064156.ece). This isn't arbitrary - it's roughly the threshold where hydrogen starts to compete with fossil alternatives in many applications.

 With current industrial electricity prices in Denmark (€0.10-€0.15/kWh), even a perfectly efficient system would produce hydrogen at ... from elecity costs alone. No amount of engineering wizardry can overcome this basic economic reality. The only path to €2/kg hydrogen requires electricity around ... or less.

### III.

Traditional electrolyzer designs try to solve this with complexity. They use expensive materials like platinum catalysts, special membranes, and high-pressure systems to maximize efficiency. A typical system costs over $1000 per kilowatt of capacity.

But what if we took a different approach? What if, instead of maximizing efficiency, we optimized for simplicity and low capital cost?

Picture an electrolyzer that's more like a very sophisticated water heater than a precision chemical plant. It operates at atmospheric pressure, using basic materials and simple designs. It's less efficient - maybe 50% instead of 80% - but it costs $100/kW or less to build.

The math changes dramatically:
At 25% utilization (matching solar availability), capital costs drop to $0.64/kg. Higher power consumption costs more - about $1.60/kg with $0.02/kWh electricity. But the total, $2.24/kg, beats the "efficient" system by a dollar per kilogram.

This reveals something profound about the economics of energy systems. When your primary input cost is rapidly falling electricity, capital costs matter more than efficiency. A low-efficiency, low-capital cost system that can eat cheap solar power directly wins against a high-efficiency system that needs expensive equipment to run 24/7.

### V.

This principle extends beyond just hydrogen production. The entire "Power-to-X" concept - turning electricity into fuels and chemicals - faces similar economics. Each conversion step adds both capital costs and energy losses. The winning solutions will be those that minimize complexity and capital intensity, even at the cost of efficiency.

This explains why the "hydrogen economy" vision of using hydrogen for everything falls flat. Many proposed applications require extensive infrastructure and face competition from simpler alternatives. The economic sweet spot lies in applications that already use hydrogen (like fertilizer production) or have few alternatives for decarbonization (like aviation fuel).

### VI.

There's a broader lesson here about how we think about green technology. We often focus on efficiency as a proxy for environmental benefit. But in a world of rapidly cheapening renewable energy, capital efficiency - the ability to build and scale solutions quickly with minimal investment - may matter more than energy efficiency.

This isn't just theory. Companies like Terraform Industries are actively pursuing this "cheaper but less efficient" approach to hydrogen production. They're betting that the economics of scale and simplicity will win over the pursuit of perfect efficiency.

The path to viable green hydrogen might require us to unlearn some of our instincts about efficiency. Sometimes, the best way to save the planet is to be a bit wasteful with energy - as long as that energy is clean and cheap enough.

[^1]: There may be a third argument about fuel for cars and planes. I think this is a largely moot point, although why this is deserves its own article at some point. Luckily, I think this is argely divorced from the larger point of this article. If you disagree, you should feel very welcome to write me an angry email.
[^2]: $\frac{39 \, \text{kWh/kg}}{51.9 \, \text{kWh/kg}} \times 100\\% = 75.14\\%$