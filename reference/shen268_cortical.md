# Shen 268 Cortical Parcellation

Cortical regions from the Shen 268-node functional parcellation (Shen et
al., 2013). Contains 2D polygon geometry for
[`ggseg::geom_brain()`](https://ggsegverse.github.io/ggseg/reference/ggbrain.html)
and 3D vertex indices for
[`ggseg3d::ggseg3d()`](https://rdrr.io/pkg/ggseg3d/man/ggseg3d.html).

## Usage

``` r
shen268_cortical()
```

## Value

A
[ggseg.formats::ggseg_atlas](https://ggsegverse.github.io/ggseg.formats/reference/ggseg_atlas.html)
object (cortical).

## References

Shen X et al. (2013). Groupwise whole-brain parcellation from
resting-state fMRI data for network node identification.
[doi:10.1016/j.neuroimage.2013.05.081](https://doi.org/10.1016/j.neuroimage.2013.05.081)

## See also

Other ggseg_atlases:
[`shen268_subcortical()`](https://ggseg.github.io/ggsegShen/reference/shen268_subcortical.md)

## Examples

``` r
shen268_cortical()
#> 
#> ── shen268_cortical ggseg atlas ────────────────────────────────────────────────
#> Type: cortical
#> Regions: 190
#> Hemispheres: left, right
#> Views: lateral, medial
#> Palette: ✔
#> Rendering: ✔ ggseg
#> ✔ ggseg3d (vertices)
#> ────────────────────────────────────────────────────────────────────────────────
#> # A tibble: 200 × 3
#>     hemi  region    label        
#>     <chr> <chr>     <chr>        
#>   1 left  egion 098 lh_Region_098
#>   2 left  egion 134 lh_Region_134
#>   3 left  egion 137 lh_Region_137
#>   4 left  egion 138 lh_Region_138
#>   5 left  egion 139 lh_Region_139
#>   6 left  egion 140 lh_Region_140
#>   7 left  egion 141 lh_Region_141
#>   8 left  egion 142 lh_Region_142
#>   9 left  egion 143 lh_Region_143
#>  10 left  egion 144 lh_Region_144
#>  11 left  egion 145 lh_Region_145
#>  12 left  egion 146 lh_Region_146
#>  13 left  egion 147 lh_Region_147
#>  14 left  egion 148 lh_Region_148
#>  15 left  egion 149 lh_Region_149
#>  16 left  egion 150 lh_Region_150
#>  17 left  egion 151 lh_Region_151
#>  18 left  egion 152 lh_Region_152
#>  19 left  egion 153 lh_Region_153
#>  20 left  egion 154 lh_Region_154
#>  21 left  egion 155 lh_Region_155
#>  22 left  egion 156 lh_Region_156
#>  23 left  egion 157 lh_Region_157
#>  24 left  egion 158 lh_Region_158
#>  25 left  egion 159 lh_Region_159
#>  26 left  egion 160 lh_Region_160
#>  27 left  egion 161 lh_Region_161
#>  28 left  egion 162 lh_Region_162
#>  29 left  egion 163 lh_Region_163
#>  30 left  egion 164 lh_Region_164
#>  31 left  egion 165 lh_Region_165
#>  32 left  egion 166 lh_Region_166
#>  33 left  egion 167 lh_Region_167
#>  34 left  egion 168 lh_Region_168
#>  35 left  egion 169 lh_Region_169
#>  36 left  egion 170 lh_Region_170
#>  37 left  egion 171 lh_Region_171
#>  38 left  egion 172 lh_Region_172
#>  39 left  egion 173 lh_Region_173
#>  40 left  egion 174 lh_Region_174
#>  41 left  egion 175 lh_Region_175
#>  42 left  egion 176 lh_Region_176
#>  43 left  egion 177 lh_Region_177
#>  44 left  egion 178 lh_Region_178
#>  45 left  egion 179 lh_Region_179
#>  46 left  egion 180 lh_Region_180
#>  47 left  egion 181 lh_Region_181
#>  48 left  egion 182 lh_Region_182
#>  49 left  egion 183 lh_Region_183
#>  50 left  egion 184 lh_Region_184
#>  51 left  egion 188 lh_Region_188
#>  52 left  egion 190 lh_Region_190
#>  53 left  egion 191 lh_Region_191
#>  54 left  egion 192 lh_Region_192
#>  55 left  egion 193 lh_Region_193
#>  56 left  egion 195 lh_Region_195
#>  57 left  egion 196 lh_Region_196
#>  58 left  egion 197 lh_Region_197
#>  59 left  egion 198 lh_Region_198
#>  60 left  egion 199 lh_Region_199
#>  61 left  egion 200 lh_Region_200
#>  62 left  egion 201 lh_Region_201
#>  63 left  egion 203 lh_Region_203
#>  64 left  egion 204 lh_Region_204
#>  65 left  egion 205 lh_Region_205
#>  66 left  egion 206 lh_Region_206
#>  67 left  egion 207 lh_Region_207
#>  68 left  egion 208 lh_Region_208
#>  69 left  egion 209 lh_Region_209
#>  70 left  egion 210 lh_Region_210
#>  71 left  egion 211 lh_Region_211
#>  72 left  egion 212 lh_Region_212
#>  73 left  egion 213 lh_Region_213
#>  74 left  egion 214 lh_Region_214
#>  75 left  egion 215 lh_Region_215
#>  76 left  egion 216 lh_Region_216
#>  77 left  egion 218 lh_Region_218
#>  78 left  egion 219 lh_Region_219
#>  79 left  egion 220 lh_Region_220
#>  80 left  egion 221 lh_Region_221
#>  81 left  egion 222 lh_Region_222
#>  82 left  egion 223 lh_Region_223
#>  83 left  egion 224 lh_Region_224
#>  84 left  egion 225 lh_Region_225
#>  85 left  egion 226 lh_Region_226
#>  86 left  egion 227 lh_Region_227
#>  87 left  egion 228 lh_Region_228
#>  88 left  egion 230 lh_Region_230
#>  89 left  egion 231 lh_Region_231
#>  90 left  egion 232 lh_Region_232
#>  91 left  egion 233 lh_Region_233
#>  92 left  egion 234 lh_Region_234
#>  93 left  egion 235 lh_Region_235
#>  94 left  egion 259 lh_Region_259
#>  95 left  egion 262 lh_Region_262
#>  96 left  egion 263 lh_Region_263
#>  97 right egion 001 rh_Region_001
#>  98 right egion 002 rh_Region_002
#>  99 right egion 003 rh_Region_003
#> 100 right egion 004 rh_Region_004
#> 101 right egion 005 rh_Region_005
#> 102 right egion 006 rh_Region_006
#> 103 right egion 007 rh_Region_007
#> 104 right egion 008 rh_Region_008
#> 105 right egion 009 rh_Region_009
#> 106 right egion 010 rh_Region_010
#> 107 right egion 011 rh_Region_011
#> 108 right egion 012 rh_Region_012
#> 109 right egion 013 rh_Region_013
#> 110 right egion 014 rh_Region_014
#> 111 right egion 015 rh_Region_015
#> 112 right egion 016 rh_Region_016
#> 113 right egion 017 rh_Region_017
#> 114 right egion 018 rh_Region_018
#> 115 right egion 019 rh_Region_019
#> 116 right egion 020 rh_Region_020
#> 117 right egion 021 rh_Region_021
#> 118 right egion 022 rh_Region_022
#> 119 right egion 023 rh_Region_023
#> 120 right egion 024 rh_Region_024
#> 121 right egion 025 rh_Region_025
#> 122 right egion 026 rh_Region_026
#> 123 right egion 027 rh_Region_027
#> 124 right egion 028 rh_Region_028
#> 125 right egion 029 rh_Region_029
#> 126 right egion 030 rh_Region_030
#> 127 right egion 031 rh_Region_031
#> 128 right egion 032 rh_Region_032
#> 129 right egion 033 rh_Region_033
#> 130 right egion 034 rh_Region_034
#> 131 right egion 035 rh_Region_035
#> 132 right egion 036 rh_Region_036
#> 133 right egion 037 rh_Region_037
#> 134 right egion 038 rh_Region_038
#> 135 right egion 039 rh_Region_039
#> 136 right egion 040 rh_Region_040
#> 137 right egion 041 rh_Region_041
#> 138 right egion 042 rh_Region_042
#> 139 right egion 043 rh_Region_043
#> 140 right egion 044 rh_Region_044
#> 141 right egion 045 rh_Region_045
#> 142 right egion 046 rh_Region_046
#> 143 right egion 047 rh_Region_047
#> 144 right egion 048 rh_Region_048
#> 145 right egion 049 rh_Region_049
#> 146 right egion 050 rh_Region_050
#> 147 right egion 053 rh_Region_053
#> 148 right egion 054 rh_Region_054
#> 149 right egion 055 rh_Region_055
#> 150 right egion 056 rh_Region_056
#> 151 right egion 059 rh_Region_059
#> 152 right egion 061 rh_Region_061
#> 153 right egion 062 rh_Region_062
#> 154 right egion 063 rh_Region_063
#> 155 right egion 064 rh_Region_064
#> 156 right egion 065 rh_Region_065
#> 157 right egion 066 rh_Region_066
#> 158 right egion 067 rh_Region_067
#> 159 right egion 068 rh_Region_068
#> 160 right egion 069 rh_Region_069
#> 161 right egion 070 rh_Region_070
#> 162 right egion 071 rh_Region_071
#> 163 right egion 072 rh_Region_072
#> 164 right egion 073 rh_Region_073
#> 165 right egion 074 rh_Region_074
#> 166 right egion 075 rh_Region_075
#> 167 right egion 076 rh_Region_076
#> 168 right egion 077 rh_Region_077
#> 169 right egion 078 rh_Region_078
#> 170 right egion 079 rh_Region_079
#> 171 right egion 080 rh_Region_080
#> 172 right egion 081 rh_Region_081
#> 173 right egion 082 rh_Region_082
#> 174 right egion 083 rh_Region_083
#> 175 right egion 084 rh_Region_084
#> 176 right egion 085 rh_Region_085
#> 177 right egion 086 rh_Region_086
#> 178 right egion 089 rh_Region_089
#> 179 right egion 090 rh_Region_090
#> 180 right egion 091 rh_Region_091
#> 181 right egion 092 rh_Region_092
#> 182 right egion 093 rh_Region_093
#> 183 right egion 094 rh_Region_094
#> 184 right egion 095 rh_Region_095
#> 185 right egion 096 rh_Region_096
#> 186 right egion 097 rh_Region_097
#> 187 right egion 098 rh_Region_098
#> 188 right egion 099 rh_Region_099
#> 189 right egion 125 rh_Region_125
#> 190 right egion 126 rh_Region_126
#> 191 right egion 128 rh_Region_128
#> 192 right egion 174 rh_Region_174
#> 193 right egion 219 rh_Region_219
#> 194 right egion 220 rh_Region_220
#> 195 right egion 221 rh_Region_221
#> 196 right egion 223 rh_Region_223
#> 197 right egion 224 rh_Region_224
#> 198 right egion 227 rh_Region_227
#> 199 right egion 259 rh_Region_259
#> 200 right egion 263 rh_Region_263
```
