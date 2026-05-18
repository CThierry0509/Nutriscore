# Clean Food Score - MVP Scoring Model

Purpose: launch a fast proof-of-concept, not a medical or regulatory certification.

## Score pillars

1. Nutrition
- Sugar: Low / Medium / High
- Sodium and saturated fat should be added in V1.1
- Ultra-processing / additive load is approximated by the Additives field

2. Transparency
- High: clear public label, nutrition data, ingredient list, allergen info
- Medium: basic label available, limited sourcing or contaminant disclosure
- Low: limited disclosure or product category with major label gaps, e.g. wine

3. Purity / contaminants
- This field does NOT claim a product contains a contaminant unless product-specific evidence exists.
- Use cautious language:
  - "category concern"
  - "public monitoring category"
  - "requires product-specific verification"
- Avoid: "this brand contains arsenic" unless supported by a source.

## MVP scoring logic

A = strong nutrition + high transparency + no known concern category
B = generally good, one moderate issue
C = acceptable but meaningful sugar/additive/processing concern
D = weak score or major disclosure gap
E = high sugar/ultra-processed or very weak nutrition profile

## Legal caution

Clean Food Score should be presented as an educational transparency tool, not as medical advice,
a lab certification, or a regulatory determination.
