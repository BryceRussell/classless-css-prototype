# Classless/Semantic Framework Prototype

Under Development

## CSS Variables

This is to document and 'lock in' the property names for the project so they dont have to be renamed and replaced later on *fingers crossed*

All values are not final and subject to change

- **--property**: `default value`

### Built in values

#### Colors:

- **--primary**: `#286cdb`
- **--primary-d1**: `#285399`
- **--primary-d2**: `#283a58`
- **--primary-l1**: `#6998e6`
- **--primary-l2**: `#a9c4f1`
- **--primary-a1**: `rgba(40, 108, 219, 0.7)`
- **--primary-a2**: `rgba(40, 108, 219, 0.4)`
- **--primary-a3**: `rgba(40, 108, 219, 0.1)`
- **--primary-a4**: `rgba(40, 108, 219, 0.05)`
- **--secondary**: `#6a3292`
- **--secondary-d1**: `#3f3249`
- **--secondary-l1**: `#b78ad7`
- **--secondary-a1**: `rgba(106, 50, 146, 0.5)`
- **--secondary-a2**: `rgba(106, 50, 146, 0.25)`
- **--valid**: `#1fa367`
- **--valid-d1**: `#1f523b`
- **--valid-l1**: `#7ae6b5`
- **--valid-a1**: `rgba(31, 163, 103, 0.5)`
- **--valid-a2**: `rgba(31, 163, 103, 0.25)`
- **--warning**: `#decd1f`
- **--warning-d1**: `#6f681f`
- **--warning-l1**: `#efe78e`
- **--warning-a1**: `rgba(222, 205, 31, 0.5)`
- **--warning-a2**: `rgba(222, 205, 31, 0.25)`
- **--invalid**: `#ea2e0f`
- **--invalid-d1**: `#751d0f`
- **--invalid-l1**: `#f79584`
- **--invalid-a1**: `rgba(234, 46, 15, 0.5)`
- **--invalid-a2**: `rgba(234, 46, 15, 0.25)`

#### Font Sizes

- **--fluid-0**: `clamp(0.88rem, 0.2vw + 0.84rem, 1rem)`
- **--fluid-1**: `clamp(1rem, 0.2vw + 0.96rem, 1.13rem)`
- **--fluid-2**: `clamp(1.1rem, 0.41vw + 1.02rem, 1.35rem)`
- **--fluid-3**: `clamp(1.21rem, 0.67vw + 1.08rem, 1.62rem)`
- **--fluid-4**: `clamp(1.33rem, 1vw + 1.14rem, 1.94rem)`
- **--fluid-5**: `clamp(1.46rem, 1.42vw + 1.2rem, 2.33rem)`
- **--fluid-6**: `clamp(1.61rem, 1.94vw + 1.25rem, 2.8rem)`
- **--fluid-7**: `clamp(1.77rem, 2.59vw + 1.29rem, 3.36rem)`
- **--fluid-8**: `clamp(1.95rem, 3.4vw + 1.31rem, 4.03rem)`
- **--fluid-9**: `clamp(2.14rem, 4.4vw + 1.32rem, 4.84rem)`

### Theme Variables

#### Base

- **--content-width**: `80ch`
- **--content-padding**: `1em`
- **--background**: `#FFF`
- **--font**: `"Helvetica", "Arial", sans-serif`
- **--line-height**: `1.25`
- **--font-size**: `--fluid-2`
- **--color**: `--gray-l3`

#### Typography

- ****: ``

- **--h1-font-size**: `--fluid-7`
- **--h2-font-size**: `--fluid-6`
- **--h3-font-size**: `--fluid-5`
- **--h4-font-size**: `--fluid-4`
- **--h5-font-size**: `--fluid-3`
- **--h6-font-size**: `--fluid-2`
- 
- **--h-color**: `--gray-l1`
- **--h-border-color**: `--gray-l16` (h1/h2 border, hr)

- **--selection-color**: `--primary`
- **--selection-background**: `#FFF`

- **--ins-color**: `--valid`
- **--del-color**: `--invalid`

- **--strong-color**: `--gray`
- **--em-color**: `root color`
- **--s-color**: `root color`
- **--u-color**: `root color`

- **--small-color**: `--gray-l8`
- **--small-font-size**: `--fluid-0` (small, sub, sup, markdown footnotes)

- **--footnote-color**: `(link color)`
- **--sup-color**: `root color`
- **--sub-color**: `root color`
- **--sub-font-size** (sub, sup, .data-footnote-backref, [aria-describedby="footnote-label"])

- **--kbd-color**: `#FFF`
- **--kbd-background**: `--gray-l1`

- **--mark-color**: `root color`
- **--mark-background**: `--warning-a1`

