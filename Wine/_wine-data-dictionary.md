# Data Dictionary
These are the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines.

## Features
`alcohol` *(numeric)*: The percentage of alcohol content in the wine, usually expressed as a volume percentage

`malic_acid` *(numeric)*: A type of acid found in grapes, which contributes to the tartness or sourness of the wine. It's often associated with green apple flavors.

`ash` *(numeric)*: The inorganic residue left after the organic material in wine has been burned off. It consists mainly of minerals.

`alcalinity_of_ash` *(numeric)*: A measure of the basicity (alkalinity) of the ash left after combustion, which can be an indicator of soil composition and grape growing conditions.

`magnesium` *(numeric)*: A mineral found in wine that can affect its taste and mouthfeel, though typically present in relatively low concentrations.

`total_phenols` *(numeric)*: A measure of the total phenolic compounds present in wine, including various antioxidants, tannins, and flavonoids. These compounds contribute to the wine's color, flavor, and mouthfeel.

`flavanoids` *(numeric)*: A subgroup of phenolic compounds found in wine, which contribute to its flavor and mouthfeel. They are responsible for some of the wine's bitterness, astringency, and antioxidant properties.

`nonflavanoid_phenols` *(numeric)*: Another subgroup of phenolic compounds found in wine, which include compounds such as stilbenes and hydroxycinnamic acids. They also contribute to the wine's sensory characteristics.

`proanthocyanins` *(numeric)*: A type of flavonoid compound found in wine, which contributes to its color, bitterness, and astringency. They are also antioxidants.

`color_intensity` *(numeric)*: The depth or darkness of the color of the wine, which can be affected by various factors including grape variety, winemaking techniques, and aging.

`hue` *(numeric)*: The shade or tint of the color of the wine.

`od` *(numeric)*: This refers to the optical density of a wine sample measured at two specific wavelengths, 280 nm and 315 nm, typically used to assess protein content and color stability in wine.

`proline` *(numeric)*: An amino acid found in grapes and wine, which can affect the taste, mouthfeel, and aging potential of the wine. It is often associated with certain flavors and aromas, such as nuttiness and bitterness.

## Output variable
`wine` *(categorical)*: Wine classification to predict.
- **Values**: `0`, `1`, `2`