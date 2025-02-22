# Data Dictionary for the Housing dataset

## Identifiers
`id`: Unique ID for each home sold.

`date`: Date of the home sale.

## House information

`bedrooms` *(numeric)*: Number of bedrooms.

`bathrooms` *(numeric)*: Number of bathrooms.
- Fractional values indicate bathrooms lacking one or more essential components (bath, shower, toilet, sink).

`sqft_living` *(numeric)*: Square footage of the apartments interior living space.

`sqft_lot` *(numeric)*: Square footage of the land space.

`floors` *(numeric)*: Number of floors.

`waterfront` *(binary)*: Does the apartment overlook a waterfront?

`view` *(numeric)*: A subjective index from `0` to `4` of how good the view of the property was.

`condition` *(numeric)*: A subjective index from `1` to `5` on the condition of the apartment.

`grade` *(numeric)*: A subjective index from `1` to `13`, where:
- `1`-`3` fall short of building construction and design.
- `7` has an average level of construction and design.
- `11`-`13` have a high quality level of construction and design.  

`sqft_above` *(numeric)*: The square footage of the interior housing space that is above ground level.

`sqft_basement` *(numeric)*: The square footage of the interior housing space that is below ground level.

`yr_built` *(numeric)*: The year the house was initially built.

`yr_renovated` *(numeric)*: The year of the house's last renovation.

`zipcode` *(categorical)*: What zipcode area the house was listed in.

`lat` *(numeric)*: Latitude.

`long` *(numeric)*: Longitude.

## Neighbor information
`sqft_living15` *(numeric)*: Average `sqft_living` of the nearest 15 neighbors.

`sqft_lot15` *(numeric)*: Average `sqft_lot` of the nearest 15 neighbors.

## Output variable

`price` *(numeric)*: Price of each home sold.