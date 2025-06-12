# Open-Source Resistor Manufacturing

## Executive Summary
This document outlines a method for manufacturing surface-mount resistors using garage-scale fabrication tools. The process is scalable, low-cost, and compatible with domestic, small business operations. With a modest investment, a home lab can produce thousands of resistors per hour with tolerances competitive with imported commercial parts.

## Motivation
Resistors are essential passive components used in all electronics. Despite their simplicity, the global supply is concentrated in a few countries, leading to fragility in the electronics supply chain. By localizing production using affordable tools and open methods, we can reduce dependency, strengthen right-to-repair efforts, and create new economic opportunities.

## Tile-Based Manufacturing Process
### Materials:
- **Substrate**: Alumina ceramic or glass tile (5" x 5")
- **Resistive Ink**: Carbon-based (graphite or carbon black in binder)
- **Conductive Ink**: Silver paste for terminals
- **Stencil Masks**: Stainless steel, photopolymer, or laser-cut film
- **Resin**: UV or epoxy for protective coating

### Tools:
- Screen printing tools or rollers
- UV laser marker or engraver (~$300–$5,000)
- Kiln or oven for baking (~300–500°C depending on ink)
- Scribing tool for slicing tiles (score & snap method)
- Multimeter or test rig for resistance verification

### Process:
1. **Mask 1**: Print carbon pattern to define resistor geometry
2. **Bake**: Sinter or dry resistive ink
3. **Mask 2**: Print silver pads at ends
4. **Optional Trim**: Use laser to adjust resistance to target value
5. **Test**: Validate resistance using inline or bulk test rig
6. **Mask 3**: Apply resin layer, leaving pads exposed
7. **Cure**: Harden resin via UV or thermal process
8. **Dice**: Slice tile into individual resistors
9. **Tape**: Feed resistors into carrier tape for packaging

## Output and Cost Estimates
- **Tile Size**: 5" x 5"
- **Component Yield**:
  - ~3,000 x 0805
  - ~7,000 x 0402
  - ~14,000 x 0202
- **Material Cost/tile**: <$5
- **Estimated Unit Cost**: <$0.01/component

## Accuracy and Tolerance
- **Initial Print**: ~5–10% tolerance
- **With Laser Trimming**: <1% tolerance

## Equipment Vendors
- Stencils: SendCutSend, OshStencils, DIY photolithography
- Laser: OMTech, ComMarker, Atomstack
- Inks: MG Chemicals, CircuitWorks, custom blends

## Next Steps
- Automate printing and trimming
- Develop inline bulk test fixture
- Publish footprint libraries for KiCad/Eagle
- Apply for grants or microfunding (FUTO, angel investors)

## Conclusion
Garage-based resistor fabrication is feasible, scalable, and economically viable. It represents the first step toward true domestic component manufacturing and sets the stage for future open-source semiconductor and sensor production.
