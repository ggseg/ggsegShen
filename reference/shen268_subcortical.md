# Shen 268 Subcortical Parcellation

Subcortical regions from the Shen 268-node functional parcellation (Shen
et al., 2013). Contains 2D polygon geometry and 3D meshes.

## Usage

``` r
data(shen268_subcortical)
```

## Format

A
[ggseg.formats::ggseg_atlas](https://ggseg.github.io/ggseg.formats/reference/ggseg_atlas.html)
object (subcortical).

## References

Shen X et al. (2013). Groupwise whole-brain parcellation from
resting-state fMRI data for network node identification.
[doi:10.1016/j.neuroimage.2013.05.081](https://doi.org/10.1016/j.neuroimage.2013.05.081)

## See also

Other ggseg_atlases:
[`shen268_cortical`](https://ggseg.github.io/ggsegShen/reference/shen268_cortical.md)

## Examples

``` r
data(shen268_subcortical)
shen268_subcortical
#> 
#> ── shen268_subcortical ggseg atlas ─────────────────────────────────────────────
#> Type: subcortical
#> Regions: 16
#> Hemispheres: NA
#> Views: axial_1, axial_2, axial_3, coronal_1, coronal_2, sagittal
#> Palette: ✔
#> Rendering: ✔ ggseg
#> ✔ ggseg3d (meshes)
#> ────────────────────────────────────────────────────────────────────────────────
#> # A tibble: 16 × 3
#>    hemi  region    label     
#>    <chr> <chr>     <chr>     
#>  1 NA    egion 058 Region_058
#>  2 NA    egion 087 Region_087
#>  3 NA    egion 088 Region_088
#>  4 NA    egion 119 Region_119
#>  5 NA    egion 121 Region_121
#>  6 NA    egion 122 Region_122
#>  7 NA    egion 123 Region_123
#>  8 NA    egion 124 Region_124
#>  9 NA    egion 127 Region_127
#> 10 NA    egion 132 Region_132
#> 11 NA    egion 135 Region_135
#> 12 NA    egion 136 Region_136
#> 13 NA    egion 229 Region_229
#> 14 NA    egion 244 Region_244
#> 15 NA    egion 245 Region_245
#> 16 NA    egion 254 Region_254
```
